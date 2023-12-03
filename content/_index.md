---
# title: My Site
toc: false
layout: hextra-home
---
{{< hextra/hero-headline >}} Hello visitor
here i post things i am working on{{< /hextra/hero-headline >}}

{{< hextra/hero-subtitle >}} Fast, batteries-included Hugo theme 
for creating beautiful static websites {{< /hextra/hero-subtitle >}}

## Explore

{{< cards >}}
  {{< card link="docs" title="Docs" icon="book-open" >}}
  {{< card link="about" title="About" icon="user" >}}
{{< /cards >}}
{{< cards >}}
  {{< card link="/" title="Image Card" image="https://source.unsplash.com/featured/800x600?landscape" subtitle="Unsplash Landscape" >}}
  {{< card link="/" title="Local Image" image="/images/card-image-unprocessed.jpg" subtitle="Raw image under static directory." >}}
  {{< card link="/" title="Local Image" image="images/space.jpg" subtitle="Image under assets directory, processed by Hugo." method="Resize" options="600x q80 webp" >}}
{{< /cards >}}

## Documentation

For more information, visit [Hextra](https://imfing.github.io/hextra).
