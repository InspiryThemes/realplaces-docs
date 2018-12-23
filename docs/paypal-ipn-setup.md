You can install and setup <strong><a href="https://wordpress.org/plugins/paypal-ipn/" target="_blank">PayPal IPN Plugin</a></strong> for payment functionality.<p></p>

<ol>
<li>Please navigate to <strong>Dashboard</strong> &rarr; <strong>Plugins</strong> &rarr; <strong>Add New</strong> and search for <strong>"PayPal IPN"</strong> as shown in the screenshot below:
<br>
<img class="light-border" src="assets/realplaces/paypal/search-for-paypal-ipn.png" alt="">
</li>
<li>Once you have found it then click the <strong>"Install Now"</strong> link under the PayPal IPN for WordPress plugin in the list of results.</li>
<li>Click the <strong>"Activate Plugin"</strong> link after the plugin has been installed.</li>
</ol>

<br>

<h2 class="entry-title">PayPal IPN Plugin Setup</h2>
<p>To setup your WordPress <strong>PayPal IPN listener</strong> you will need to copy your IPN URL from the plugin’s general settings tab into your PayPal account profile’s IPN settings panel.</p>

<ol>
<li>Kindly navigate to <strong>Dashboard</strong> &rarr; <strong>Settings</strong> &rarr; <strong>PayPal IPN</strong>.</li>
<li>Highlight the <strong>PayPal IPN Primary URL</strong> and copy it to your clipboard by pressing <strong>Ctrl+C / Cmd+C</strong>.</li>
<li>If you wish to enable logging for troubleshooting purposes, check the box and click <strong>Save</strong> as shown in the screenshot.
<br>
<img class="light-border" src="assets/realplaces/paypal/wordpress-paypal-ipn-general-settings.png" alt="">
</li>
<li>Login to your <strong>PayPal account</strong>.</li>
<li>Click the <strong>Profile</strong> link on the <strong>My Account</strong> tab.</li>
<li>Click <strong>Instant Payment Notification Preferences</strong> in the <strong>Selling Preferences</strong> section.</li>
<li>Click <strong>Choose IPN Settings</strong>.</li>
<li>Enter your <strong>IPN URL</strong> that you copied from the plugin settings.</li>
<li>Click <strong>Receieve IPN messages (Enabled)</strong> to activate your IPN listener.</li>
<li>Click <strong>Save</strong> to save your changes.
<br>
<img class="light-border" src="assets/realplaces/paypal/wordpress-paypal-ipn-profile-config.png" alt="">
