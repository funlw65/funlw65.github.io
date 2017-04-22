-= [About](about.md) -=- [Blog](news.md) =-
<hr />

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/funlw65/funlw65.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```c
typedef enum { MANUAL = 0, EOS} lens_t;
typedef enum { EOSMANUAL = 0, EOS50MM12, EOS50MM14, EOS50MM18, EOS85MM12, EOS85MM18} eos_t;
typedef enum { M = 0, AV, TV} cameramode_t;

/* -- Global variables ---------------------------------------------- */ 
uint8_t  EV; /* using only the integer values of it                   */
float    LUX;/* this comes form the TSL2591 library                   */
uint16_t ISO;/* current ISO - index to the ISO_values[] array         */
uint8_t  Av; /* current aperture - index to the Av_values[] array     */
uint8_t  Tv; /* current shutter speed - index to the ST_speed[] array */
lens_t   LensType; /* current lens type                               */
eos_t    EOSModel; /* current EOS lens model                          */
cameramode_t Mode; /* current camera mode set by user                 */
/* ------------------------------------------------------------------ */

/** film sensitivity in ISO values - 160 will be treated as 100 ISO */
const uint16_t ISO_values[8]={25,50,100,200,400,800,1600,3200};

```
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/funlw65/funlw65.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact
Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
