Small repository for experimenting with web components.

Google developer resource:
https://developers.google.com/web/fundamentals/web-components/customelements

To feature detect custom elements, check for the existence of window.customElements:

<code>const supportsCustomElementsV1 = 'customElements' in window;</code>