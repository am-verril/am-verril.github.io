---
title: "links"
draft: false
---

{{- if .Lastmod }}
    {{- $lastmod := .Lastmod.Format "02.01.2006" }}
    {{- if ne $lastmod $pubdate }}
        <div class="post-info-last-mod">
            (Updated: 
            <time datetime="{{ .Lastmod }}" title="{{ .Lastmod }}">
                {{ $lastmod }}
            </time>)
        </div>
    {{- end }}
{{- end }}

- [The Colourful Mr Eggleston](https://www.youtube.com/watch?v=Se8ukKv-jvY)
- [Duchamp, Fountain](https://www.youtube.com/watch?v=FmjSUyyc-3M)
- [The Trouble With Minimum Parking Requirements](https://www.vtpi.org/shoup.pdf)
- [The Pension Puzzle](https://www.imf.org/external/pubs/ft/issues/issues29/index.htm)
- [The Economics of Contracts](https://edwardknings.substack.com/p/the-economics-of-contracts)


