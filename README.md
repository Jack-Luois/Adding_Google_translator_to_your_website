# Adding_Google_translator_to_your_website

`Google Translator` also let you add `multilingual` ability to your own websites with the help of API. For this, you need to follow these steps:

Step 1 :	Add `<div id="google_translate_element"></div>` to your `HTML` code where you want to display the translation dropdown.

Step 2 : Add 

              <script type="text/javascript">
		            function googleTranslateElementInit() {
			            new google.translate.TranslateElement(
				            {pageLanguage: 'en'},'google_translate_element');
		            }
	            </script>
	            <script type="text/javascript" src="https://translate.google.com/
              translate_a/element.js?cb=googleTranslateElementInit"></script>
to the end of the body.
