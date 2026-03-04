
# Obsidian Defaults

> [!note]
> Lorem ipsum dolor sit amet

> [!info]
> Lorem ipsum dolor sit amet

> [!todo]
> Lorem ipsum dolor sit amet

> [!abstract]
> Lorem ipsum dolor sit amet
> Aliases: `summary`, `tldr`

> [!tip]
> Lorem ipsum dolor sit amet
> Aliases: `hint`, `important`

> [!success]
> Lorem ipsum dolor sit amet
> Aliases: `check`, `done`

> [!question]
> Lorem ipsum dolor sit amet
> Aliases: `help`, `faq`

> [!warning]
> Lorem ipsum dolor sit amet
> Aliases: `caution`, `attention`

> [!failure]
> Lorem ipsum dolor sit amet
> Aliases: `fail`, `missing`

> [!danger]
> Lorem ipsum dolor sit amet
> Alias: `error`

> [!bug]
> Lorem ipsum dolor sit amet

> [!example]
> Lorem ipsum dolor sit amet

> [!quote]
> Lorem ipsum dolor sit amet
> Alias: `cite`

> [!faq]- Are callouts foldable?
> Yes! In a foldable callout, the contents are hidden when the callout is collapsed.

> [!tip] Callouts can have custom titles
> Like this one.

> [!tip] Title-only callout

> [!question] Can callouts be nested?
> > [!todo] Yes!, they can.
> > > [!example]  You can even use multiple layers of nesting.

# Wikipedia Style Infobox

> [!infobox]
>
> ## Dansby Swanson
>
> ![[dansby-swanson.jpg]]
> Dansby Swanson details decision to sign with the Chicago Cubs
>
> ### Chicago Cubs – No. 7
>
> | Type     | Stat                                          |
> | -------- | --------------------------------------------- |
> | Position | Shortstop                                     |
> | Born     | February 11, 1994 (age 28), Kennesaw, Georgia |
> | Bats     | Right                                         |
> | Throws   | Right                                         |
>
> ### MLB debut
>
> August 17, 2016, for the Atlanta Braves
>
> ### MLB statistics
>
> | Type | Stat |
> | ---- | ---- |
> | AVG  | .256 |
> | HR   | 103  |
> | RBI  | 413  |
>
> ### Teams
>
> - Atlanta Braves (2016-2022)
> - Chicago Cubs (2023-)
>
> ### Career highlights and awards
>
> - All-Star (2022)
> - World Series champion (2021)
> - Gold Glove Award (2022)

# Folder Trees

> [!folder] Folder
>
> - 📁 Folder _`           `← root folder_
>   - 📄 Item 1 _`         `← some item in the folder_
>   - 📁 Subfolder 1 _`    `← another folder_
>     - 📄 Subitem 1-1
>     - 📄 Subitem 1-2
>   - 📁 Subfolder 2
>     - 📄 Subitem 2-1
>     - 📄 Subitem 2-2
>     - 📁 Subsubfolder
>       - 📄 ==Name==.jpg _`   `… Some variable name?_
>       - …

# Timeline

> [!timeline|red] Title
> Lorem, ipsum dolor sit amet consectetur, adipisicing elit.

> [!timeline|green] Title 2
> Lorem, ipsum dolor sit amet consectetur, adipisicing elit.

> [!timeline|blue] Title 3
> Lorem, ipsum dolor sit amet consectetur, adipisicing elit.

# Rose Frame

> [!roseframe]
> Lorem, ipsum dolor sit amet consectetur, adipisicing elit. Lorem, ipsum dolor sit amet consectetur, adipisicing elit.

# Labels

> [!bug|label] Lorem, ipsum dolor sit amet
> Lorem, ipsum dolor sit amet consectetur, adipisicing elit. Lorem, ipsum dolor sit amet consectetur, adipisicing elit.

> [!info|label] Lorem, ipsum dolor sit amet
> Lorem, ipsum dolor sit amet consectetur, adipisicing elit. Lorem, ipsum dolor sit amet consectetur, adipisicing elit.

# Asides

> [!info|aside-r]
> Your text here

> [!bug|aside-l]
> Your text here

# Tabs

> [!tabbed]
>
> <label>First<input type="radio" name="test" />l</label>
>
> > Lorem, ipsum dolor sit amet consectetur, adipisicing elit. (First)
> > [[Obsidian CSS|Internal Link]] > > **bold** _italic_
>
> <label>Second<input type="radio" name="test" /></label>
>
> > Lorem, ipsum dolor sit amet consectetur, adipisicing elit. (Second)
> > [External Link](https://google.com) > > $\LaTeX$
>
> <label>Third<input type="radio" name="test" />l</label>
>
> > Lorem, ipsum dolor sit amet consectetur, adipisicing elit. (Third)
> >
> > - bullet item
> > - [ ] checkbox
> > - [x] `#tag`

# Theorem Frame

> [!theorem] **Theorem 1.4.49** (Dominated convergence theorem).
> Let $(X,B,\mu)$ be a measure space, and let $f_1, f_2, \dots: X \rightarrow C$ be a sequence of measurable functions that converge pointwise $\mu$-almost everywhere to a measurable limit $f:X \rightarrow C$. Suppose that there is an unsigned absolutely integrable function $G:X \rightarrow [0,+\infty]$ such that $|f_n|$ are pointwise $\mu$-almost everywhere bounded by $G$ for each $n$. Then we have
> $$\lim_{n \rightarrow \infty}\int_{X}f_nd\mu = \int_{X}f~d\mu$$