# Develcooking's Hugo Theme

Ein einfaches Hugo Theme welches von [kochenmit.style](https://github.com/develcooking/kochenmit.style) genutzt werden soll

Original geschrieben von Luke Smith übersetztt von develcooking

## Zum Loslegen

```sh
hugo new site new-site
cd new-site
git clone https://github.com/develcooking/glulo themes/glulo
echo "theme = 'glulo'" >> config.toml
cp themes/glulo/static/style.css static/
```

## Anderes

- Erstelle einen RSS feed mit dem Eintrag in `/index.xml`
- Die Styleforlage ist in `/style.css` plaziert und beinhaltet auch andere wichtige Dinge
- Wenn ein Post Taggs enthält wird eine Liste mit ihnen am Ende des Posts plaziert
- `nextprev.html` fügt einen Link zum Nächsten und Zuvorigen Artikel am Ende der Seite hinzu.
- `taglist.html` verlinkt alle Tags, mit denen ein Artikel getaggt ist, für verwandte Inhalte.
