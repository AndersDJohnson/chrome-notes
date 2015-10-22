# chrome-notes
Chrome notes.

## Insecure Temporary
Launches Chrome with with web security disabled but in a temporary profile to protect your data.
Sometimes useful for development, e.g. if you need to make [CORS] requests.

```
chrome.exe --disable-web-security --allow-running-insecure-content --user-data-dir=C:\Windows\Temp\my-chrome-temp-1
```

[CORS]: https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS
