# Mybooking reservation process - Boiler plate html example

Copy the repository to a folder and open the 'index.html' file

**Please note that you need to have a Mybooking customer ID and api key.**

------------------------------------------------------------------------------

**For more information:**
https://docs.mybooking.es/motor-de-reservas/desarrolladores/#introduccion

------------------------------------------------------------------------------

## IMPORTANT
-  For it to work you need a configuration file, create a 'init-vars.js' file inside *assets > js* dir with a structure similar to this:

		const mybooking_init_vars = {
				"mybooking_site_url": "",
				"mybooking_api_url_prefix": "https://[ACCOUNT_ID].mybooking.es",
				"mybooking_account_id": "[ACCOUNT_ID]",
				"mybooking_api_key": "[API_KEY]",
				"mybooking_choose_products_page": "search-result.html",
				"mybooking_checkout_page": "checkout.html",
				"mybooking_summary_page": "summary.html",
				"mybooking_terms_page": null,
				"mybooking_detail_pages": "",
				"mybooking_detail_pages_url_prefix": "products",
				"mybooking_selector_in_process": "form",
				"mybooking_phone_utils_path": "./assets/js/intlTelInput-utils.js",
				"mybooking_custom_loader": "false",
				"mybooking_js_select2": "false"
		};



