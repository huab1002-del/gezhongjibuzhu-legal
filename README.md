import * as WebBrowser from 'expo-web-browser';

const handlePrivacyPolicy = async ( ) => {
  await WebBrowser.openBrowserAsync(
    'https://yourusername.github.io/gezhongjibuzhu-legal/PRIVACY_POLICY.md'
   );
};

// 在设置屏幕中添加按钮
<SettingItem
  icon="doc.text"
  title="隐私政策"
  onPress={handlePrivacyPolicy}
  color="#3498DB"
/>
