# Four Branches of Modern Slasher History

A responsive, single-page visual history of four major American horror lines:

- *Friday the 13th*
- *A Nightmare on Elm Street*
- *Halloween*
- *The Texas Chain Saw Massacre*

The page keeps the poster-like design of the original concept - double border, strong branch colors, and modular timeline cards - while restoring the detailed production history, film lists, sequel continuities, and director offshoots. Each historical foundation now appears inside the branch it feeds instead of in a separate shared strip. Character portraits have been removed; each branch header is text-only.

## Project structure

```text
slasher-history-site-corrected/
├── index.html
└── README.md
```

The site uses plain HTML and CSS with no framework, package manager, build command, JavaScript, external font dependency, or image assets. It is a single self-contained file.

## Preview locally

You can open `index.html` directly in a browser. To preview it through a local web server, run this command from the project folder:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages** in the GitHub repository.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)` folder, then click **Save**.
7. GitHub will display the public site address after deployment finishes.

## Content included

### Friday the 13th line

- Sean S. Cunningham and Wes Craven's work on *Together* and *The Last House on the Left*
- Their early mentorship of Steve Miner
- Cunningham's family-film detour through *Here Come the Tigers* and *Manny's Orphans*
- The production team that carried into the original *Friday the 13th*
- The influence of *Halloween*
- Every released film from the 1980 original through the 2009 remake
- A dedicated Steve Miner subbranch containing all 14 of his directed features

### A Nightmare on Elm Street line

- The point where Wes Craven branches away after *The Last House on the Left*
- Craven's development from his early features through the 1984 original
- Craven's post-Freddy feature directing work through *Scream 4*
- Every Nightmare on Elm Street sequel, from 1985's *Freddy's Revenge* through the 2010 remake
- Selected television movies

### Halloween line

- Bob Clark's *Black Christmas* and his later-recalled conversation with John Carpenter
- The 1978 original
- John Carpenter's horror directing filmography
- Every sequel grouped by the Original/Thorn, Anthology, H20, Rob Zombie, and Blumhouse continuities

### Texas Chain Saw Massacre line

- Bryanston's distribution of *Deep Throat* and later acquisition of TCM distribution rights
- Tobe Hooper and Kim Henkel's independent production story
- The Bryanston distribution deal and its aftermath
- Hooper's directed features and television landmarks
- All nine released TCM films through the 2022 installment

## Customize the design

The principal colors are CSS custom properties near the top of `index.html`:

```css
--f13: #a52420;
--elm-red: #9f261f;
--elm-green: #315f3c;
--halloween: #d86b12;
--tcm: #a77820;
--tcm-accent: #d2ad52;
```

The layout displays four columns on large screens, two columns on medium screens, and one column on phones. No content is removed at smaller sizes.

## Accuracy notes

- Bryanston distributed *Deep Throat*; it did not produce it.
- Bryanston acquired distribution rights to the completed *Texas Chain Saw Massacre*; Hooper and Henkel's production was financed independently by Texas investors.
- The filmmaker who directed *Friday the 13th Part 2* and *Part III* is **Steve Miner**. Sean S. Cunningham is a different filmmaker.

Selected research links are included at the bottom of the webpage.
