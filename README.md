Copyright (C) 2013 by BIPS

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

About
	Bitcoin payments via BIPS for Zen Cart.

Version 0.2
	Currency convert between all currencies automatically.
	
System Requirements:
	BIPS API, Secret
	Zen Cart. Tested against version 1.5.1
	PHP 5+
	Curl PHP Extension
  
Configuration Instructions:
	1. Upload files to your Zen Cart installation.
	2. Go to your Zen Cart administration. Modules -> Payment then Bitcoins via BIPS. Click install.
	3. In BIPS Callback URL (https://bips.me/merchant) Enter the link to your callback of BIPS Zen Cart Payment Module. (http://YOUR_ZEN_CART_URL/bips_callback.php)
	4. Enter a strong Secret in Merchant SECRET.
	5. In module settings "API" <- set your BIPS API Key, which can be generate under API Keys, Invoice.
	6. In module settings "Secret" <- Enter your BIPS Merchant Secret.