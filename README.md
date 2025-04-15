# Generic GET Request

A custom tag template for Google Tag Manager that makes it easy to send any GET request from GTM, as is often needed when sending data to endpoints like webhooks, APIs, or GTM Server-Side. Can also be used to send generic pixel requests.

Note: due to limitations with the GTM sandboxed environment, some aspects of the GET requests are not customizable, such as HTTP headers or the URL fragment (the text after the `#` character in the URL).