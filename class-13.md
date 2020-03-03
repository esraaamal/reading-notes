


# **HTML5 Storage** is a specification named Web Storage

## Historically, web applications have had none of these luxuries.
  **Cookies**:  were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful



### What we really want is:

a lot of storage space
on the client
that persists beyond a page refresh
and isn’t transmitted to the server

- Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.
- userData allows web pages to store up to 64 KB of data per domain,
 -cookies, is a data data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you.