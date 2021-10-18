# op-help-site-dev

A help site for all learners and staff in the **Bachelor of Information** programme at **Otago Polytechnic**. This site uses [Geekdoc](https://github.com/thegeeklab/hugo-geekdoc), a simple **Hugo** theme for documentation.

## Getting Started

As mentioned, this site uses **Geekdoc**. To use this theme:

1. Create a new directory called `themes`.

```md
mkdir themes 
```

2. Change to the `themes` directory.

```md
cd themes
```

3. Clone the **Geekdoc** git repository.

```md
git clone https://github.com/thegeeklab/hugo-geekdoc.git themes/hugo-geekdoc
```

4. Build required theme assets with **gulp**.

```md
npx gulp default
```

5. Change to **root** directory.

```md
cd ..
```

6. Run the help site.

```md 
hugo server -D
```
