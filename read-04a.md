Review:

MDN URLSearchParams built-in class (Links to an external site.)
    - 
    Properties
Location.ancestorOrigins
Is a static DOMStringList containing, in reverse order, the origins of all ancestor browsing contexts of the document associated with the given Location object.
Location.href
Is a stringifier that returns a USVString containing the entire URL. If changed, the associated document navigates to the new page. It can be set from a different origin than the associated document.
Location.protocol
Is a USVString containing the protocol scheme of the URL, including the final ':'.
Location.host
Is a USVString containing the host, that is the hostname, a ':', and the port of the URL.
Location.hostname
Is a USVString containing the domain of the URL.
Location.port
Is a USVString containing the port number of the URL.
Location.pathname
Is a USVString containing an initial '/' followed by the path of the URL.
Location.search
Is a USVString containing a '?' followed by the parameters or "querystring" of the URL. Modern browsers provide URLSearchParams and URL.searchParams to make it easy to parse out the parameters from the querystring.
Location.hash
Is a USVString containing a '#' followed by the fragment identifier of the URL.



toString() returns query string (Links to an external site.)

URLSearchParams.toString()


Using the url "hash":

Built-in Location Object (Links to an external site.)

Properties
Location.ancestorOrigins
Is a static DOMStringList containing, in reverse order, the origins of all ancestor browsing contexts of the document associated with the given Location object.
Location.href
Is a stringifier that returns a USVString containing the entire URL. If changed, the associated document navigates to the new page. It can be set from a different origin than the associated document.
Location.protocol
Is a USVString containing the protocol scheme of the URL, including the final ':'.
Location.host
Is a USVString containing the host, that is the hostname, a ':', and the port of the URL.
Location.hostname
Is a USVString containing the domain of the URL.
Location.port
Is a USVString containing the port number of the URL.
Location.pathname
Is a USVString containing an initial '/' followed by the path of the URL.
Location.search
Is a USVString containing a '?' followed by the parameters or "querystring" of the URL. Modern browsers provide URLSearchParams and URL.searchParams to make it easy to parse out the parameters from the querystring.
Location.hash
Is a USVString containing a '#' followed by the fragment identifier of the URL.
Location.origin Read only
Returns a USVString containing the canonical form of the origin of the specific location.
Methods
Location.assign()
Loads the resource at the URL provided in parameter.
Location.reload()
Reloads the current URL, like the Refresh button.
Location.replace()
Replaces the current resource with the one at the provided URL (redirects to the provided URL). The difference from the assign() method and setting the href property is that after using replace() the current page will not be saved in session History, meaning the user won't be able to use the back button to navigate to it.
Location.toString()
Returns a USVString containing the whole URL. It is a synonym for HTMLHyperlinkElementUtils.href, though it can't be used to modify the value.
Hash change event
