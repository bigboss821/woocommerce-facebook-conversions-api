# woocommerce-facebook-conversions-api
woocommerce-facebook-conversions-api

# WooCommerce Facebook Conversions API

A WordPress plugin that sends WooCommerce events to Facebook's Conversions API server-side for improved tracking and privacy compliance.

## Features

### Core Functionality
- ✅ Server-side event tracking (no browser JavaScript required)
- ✅ All standard e-commerce events: PageView, AddToCart, InitiateCheckout, Purchase
- ✅ Advanced events: ViewContent, ViewCart, CompleteRegistration, Search, AddToWishlist
- ✅ Event deduplication using unique event IDs
- ✅ User data hashing for privacy compliance (GDPR, CCPA)

### Admin Interface
- ✅ Settings page under "Facebook CAPI" menu
- ✅ Configuration for Facebook Pixel ID, Access Token, Test Event Code
- ✅ Debug mode for event logging
- ✅ Test connection functionality
- ✅ Last error display with timestamps

### Event Tracking
- ✅ **PageView**: Tracked on every page load
- ✅ **AddToCart**: When products are added to cart
- ✅ **InitiateCheckout**: When checkout process begins
- ✅ **Purchase**: When orders are completed
- ✅ **ViewContent**: When viewing product pages
- ✅ **ViewCart**: When viewing cart page
- ✅ **CompleteRegistration**: When users register
- ✅ **Search**: When users search products
- ✅ **AddToWishlist**: YITH Wishlist support

### Advanced Features
- ✅ Product attribute tracking (brand, color, size)
- ✅ Category/shop page tracking
- ✅ Cart update tracking
- ✅ Currency conversion handling
- ✅ Comprehensive error logging
- ✅ Test mode using Facebook test event codes

## Installation

### Method 1: Upload Plugin
1. Download the plugin ZIP file
2. Go to WordPress Admin → Plugins → Add New → Upload Plugin
3. Choose the ZIP file and click "Install Now"
4. Activate the plugin

### Method 2: Manual Installation
1. Extract the plugin files
2. Upload the `woocommerce-facebook-conversions-api` folder to `/wp-content/plugins/`
3. Go to WordPress Admin → Plugins
4. Activate "WooCommerce Facebook Conversions API"

## Configuration

### Step 1: Get Facebook Credentials
1. Go to [Facebook Business Manager](https://business.facebook.com/)
2. Navigate to Events Manager
3. Create or select your Pixel
4. Get your **Pixel ID** and **Access Token**

### Step 2: Configure Plugin
1. Go to WordPress Admin → **Facebook CAPI**
2. Enter your Facebook Pixel ID
3. Enter your Access Token
4. (Optional) Add Test Event Code for testing
5. Enable Debug Mode if needed
6. Click "Save Changes"

### Step 3: Test Connection
1. Click "Test Connection" button
2. Check for success message
3. Verify events in Facebook Events Manager

## Usage

The plugin automatically tracks events when:
- Users browse your store (PageView)
- Products are added to cart (AddToCart)
- Checkout process begins (InitiateCheckout)
- Orders are completed (Purchase)
- Product pages are viewed (ViewContent)
- Cart page is viewed (ViewCart)
- Users register (CompleteRegistration)
- Users search (Search)
- Products are added to wishlist (AddToWishlist)

## Requirements

- WordPress 5.0 or higher
- WooCommerce 5.0 or higher
- PHP 7.4 or higher
- Facebook Business Manager account

## Privacy Compliance

This plugin includes features for privacy compliance:
- User data hashing (SHA256)
- Configurable data collection
- GDPR and CCPA ready
- Server-side processing

## Troubleshooting

### Common Issues

1. **Events not sending**
   - Check Facebook Pixel ID and Access Token
   - Verify WooCommerce is active
   - Enable debug mode and check logs

2. **API errors**
   - Check "Last Error" in settings
   - Verify Access Token permissions
   - Test connection using the test button

3. **Missing events**
   - Ensure proper WooCommerce hooks are firing
   - Check if events are being filtered
   - Verify Facebook Pixel configuration

### Debug Mode

Enable debug mode to log events to WordPress debug log:
1. Go to Facebook CAPI settings
2. Check "Enable debug logging"
3. Check your WordPress debug log for events

## Support

For support and questions:
- Check the troubleshooting section above
- Review Facebook's Conversions API documentation
- Enable debug mode for detailed logging

## Changelog

### Version 1.0.0
- Initial release
- Complete event tracking implementation
- Admin interface with settings
- Error handling and logging
- Privacy compliance features

## License

GPL v2 or later

---

# বাংলা নির্দেশিকা

## বৈশিষ্ট্যসমূহ

### মূল কার্যকারিতা
- ✅ সার্ভার-সাইড ইভেন্ট ট্র্যাকিং (ব্রাউজার JavaScript প্রয়োজন নেই)
- ✅ সব স্ট্যান্ডার্ড ই-কমার্স ইভেন্ট: PageView, AddToCart, InitiateCheckout, Purchase
- ✅ উন্নত ইভেন্ট: ViewContent, ViewCart, CompleteRegistration, Search, AddToWishlist
- ✅ ইউনিক ইভেন্ট ID দিয়ে ডুপ্লিকেশন প্রতিরোধ
- ✅ গোপনীয়তা নীতিমালা অনুযায়ী ব্যবহারকারীর ডাটা হ্যাশিং

### প্রশাসনিক ইন্টারফেস
- ✅ "Facebook CAPI" মেনুতে সেটিংস পেজ
- ✅ Facebook Pixel ID, Access Token, Test Event Code কনফিগারেশন
- ✅ ইভেন্ট লগিংয়ের জন্য ডিবাগ মোড
- ✅ টেস্ট কানেকশন ফাংশনালিটি
- ✅ সময়সহ শেষ ত্রুটি প্রদর্শন

## ইনস্টলেশন

### পদ্ধতি ১: প্লাগইন আপলোড
1. প্লাগইন ZIP ফাইল ডাউনলোড করুন
2. WordPress Admin → Plugins → Add New → Upload Plugin এ যান
3. ZIP ফাইল নির্বাচন করে "Install Now" ক্লিক করুন
4. প্লাগইন অ্যাক্টিভেট করুন

### পদ্ধতি ২: ম্যানুয়াল ইনস্টলেশন
1. প্লাগইন ফাইলগুলি এক্সট্র্যাক্ট করুন
2. `woocommerce-facebook-conversions-api` ফোল্ডারটি `/wp-content/plugins/` এ আপলোড করুন
3. WordPress Admin → Plugins এ যান
4. "WooCommerce Facebook Conversions API" অ্যাক্টিভেট করুন

## কনফিগারেশন

### ধাপ ১: Facebook ক্রেডেনশিয়াল পাওয়া
1. [Facebook Business Manager](https://business.facebook.com/) এ যান
2. Events Manager এ নেভিগেট করুন
3. আপনার Pixel তৈরি বা নির্বাচন করুন
4. আপনার **Pixel ID** এবং **Access Token** পান

### ধাপ ২: প্লাগইন কনফিগার
1. WordPress Admin → **Facebook CAPI** এ যান
2. আপনার Facebook Pixel ID দিন
3. আপনার Access Token দিন
4. (ঐচ্ছিক) টেস্টিংয়ের জন্য Test Event Code যোগ করুন
5. প্রয়োজন হলে Debug Mode সক্রিয় করুন
6. "Save Changes" ক্লিক করুন

### ধাপ ৩: কানেকশন টেস্ট
1. "Test Connection" বাটনে ক্লিক করুন
2. সফলতার বার্তা দেখুন
3. Facebook Events Manager এ ইভেন্ট যাচাই করুন

## প্রয়োজনীয়তা

- WordPress 5.0 বা উচ্চতর
- WooCommerce 5.0 বা উচ্চতর
- PHP 7.4 বা উচ্চতর
- Facebook Business Manager অ্যাকাউন্ট

## সমস্যা সমাধান

### সাধারণ সমস্যা

1. **ইভেন্ট পাঠানো হচ্ছে না**
   - Facebook Pixel ID এবং Access Token যাচাই করুন
   - WooCommerce সক্রিয় আছে কিনা দেখুন
   - ডিবাগ মোড সক্রিয় করে লগ দেখুন

2. **API ত্রুটি**
   - সেটিংসে "Last Error" দেখুন
   - Access Token অনুমতি যাচাই করুন
   - টেস্ট বাটন দিয়ে কানেকশন পরীক্ষা করুন

3. **ইভেন্ট অনুপস্থিত**
   - সঠিক WooCommerce hooks কাজ করছে কিনা দেখুন
   - ইভেন্ট ফিল্টার হচ্ছে কিনা যাচাই করুন
   - Facebook Pixel কনফিগারেশন যাচাই করুন 
