# Adding_Google_translator_to_your_website

![made-with-HTML](https://img.shields.io/badge/HTML-5.0-ff5230?style=for-the-badge&logo=HTML5)
![made-with-javascript](https://img.shields.io/badge/javascript--F7DF1E?style=for-the-badge&logo=JavaScript)
![made-with-google](https://img.shields.io/badge/Google_translate--4285F4?style=for-the-badge&logo=Google+Translate)

`Google Translator` also let you add `multilingual` ability to your own websites with the help of API. For this, you need to follow these steps:

Step 1 :	Add `<div id="google_translate_element"></div>` to your `HTML` code where you want to display the translation dropdown.

Step 2 : Add 

            <script type="text/javascript">
		    function googleTranslateElementInit() {
			new google.translate.TranslateElement(
			    {pageLanguage: 'en'},'google_translate_element');
		    }
	        </script>
	        <script type="text/javascript" src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
to the end of the body.
