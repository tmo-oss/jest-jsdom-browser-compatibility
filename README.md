# jest-jsdom-browser-compatibility

This is a matrix of issues and risks of using Jest with JSDOM to test browser applications.  This will include several sub projects with example tests to demonstrate the failures.

## Test Case Comparison Matrix

https://docs.google.com/spreadsheets/d/1BZ6NxHiXU7yRJN50jRyrBWhjghSXiq-s-Rw3xthGTS0/edit?usp=sharing

## Test cases source code

In [testcases-src](testcases-src/)

- Test case 1: [tc1-contenteditable](testcases-src/tc1-contenteditable)
- Test case 2: [tc2-selector-not-working-the-same](testcases-src/tc2-selector-not-working-the-same)
- Test case 3: [tc3-style-property-not-change](testcases-src/tc3-style-property-not-change)
- Test case 4: [tc4-notification-api-missing](testcases-src/tc4-notification-api-missing)
- Test case 5: [tc5-not-support-crypto-api](testcases-src/tc5-not-support-crypto-api)
- Test case 6: [tc6-not-support-TextEncoder](testcases-src/tc6-not-support-TextEncoder)
- Test case 7: [tc7-not-support-innerText](testcases-src/tc7-not-support-innerText)
- Test case 8: [tc8-wrong-style-value-svg](testcases-src/tc8-wrong-style-value-svg)
- Test case 9: [tc9-style-calc-wrong](testcases-src/tc9-style-calc-wrong)
- Test case 10: [tc10-not-support-css-custom-properties](testcases-src/tc10-not-support-css-custom-properties)
- Test case 11: [tc11-border-value-wrong](testcases-src/tc11-border-value-wrong)
- Test case 12: [tc12-not-implement-offsetTop](testcases-src/tc12-not-implement-offsetTop)
- Test case 13: [tc13-not-support-svg-attributes](testcases-src/tc13-not-support-svg-attributes)
- Test case 14: [tc14-bug-in-DOMParser](testcases-src/)
- Test case 15: [tc15-PointerEvent-not-available](testcases-src/tc15-PointerEvent-not-available)
- Test case 16: [tc16-bug-in-FormData](testcases-src/tc16-bug-in-FormData)
- Test case 17: [tc17-CssStyleDeclaration-not-apply-color-style](testcases-src/tc17-CssStyleDeclaration-not-apply-color-style)
- Test case 18: [tc18-not-ignore-invalid-style-properties](testcases-src/tc18-not-ignore-invalid-style-properties)
- Test case 19: [tc19-as-attribute-not-implement-in-Link-tag](testcases-src/tc19-as-attribute-not-implement-in-Link-tag)
- Test case 20: [tc20-not-implement-MessageChannel](testcases-src/tc20-not-implement-MessageChannel)
- Test case 21: [tc21-not-support-Cache-API](testcases-src/tc21-not-support-Cache-API)
- Test case 22: [tc22-inline-background-0-stripped](testcases-src/tc22-inline-background-0-stripped)
- Test case 23: [tc23-not-support-layout-properties](testcases-src/tc23-not-support-layout-properties)
- Test case 24: [tc24-not-support-Image.decode-method](testcases-src/tc24-not-support-Image.decode-method)
- Test case 25: [tc25-Text.textContent-not-inherit-from-Node.textContent](testcases-src/tc25-Text.textContent-not-inherit-from-Node.textContent)
- Test case 26: [tc26-missing-support-window.performance.navigation](testcases-src/tc26-missing-support-window.performance.navigation)
- Test case 27: [tc27-querySelectorAll-not-support-namespaced-attribute](testcases-src/tc27-querySelectorAll-not-support-namespaced-attribute)
- Test case 28: [tc28-not-support-pseudo-element](testcases-src/tc28-not-support-pseudo-element)
- Test case 29: [tc29-not-support-worker-thread-api](testcases-src/tc29-not-support-worker-thread-api)
- Test case 30: [tc30-hsl-color-effect-different](testcases-src/tc30-hsl-color-effect-different)
- Test case 31: [tc31-cannot-get-video-textTracks](testcases-src/tc31-cannot-get-video-textTracks)
- Test case 32: [tc32-not-implement-Selection-API](testcases-src/tc32-not-implement-Selection-API)
- Test case 33: [tc33-window.getComputedStyle-not-work](testcases-src/tc33-window.getComputedStyle-not-work)
