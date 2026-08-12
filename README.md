# Noisy Top-k Gating and Load Balancing

I took the inspiration from Andrej-Karpathy to write this repo, built from my handwritten notes on Shazeer et al. (2017).

## Files

- `index.html` - complete article
- `style.css` - page styling
- `assets/` - diagrams and selected handwritten note pages

## Run locally

Open `index.html` in a browser.

For the best editing workflow in VS Code, install the Live Server extension and use:

`Open with Live Server`

The equations use MathJax from jsDelivr, so an internet connection is needed for equation rendering.

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, and `assets/`.
3. Go to repository Settings -> Pages.
4. Select the branch containing these files and the root folder.
5. Save.
6. GitHub will provide the public Pages URL.

## Writing style

The article intentionally uses a long-form research-note structure:

- problem first
- intuition before formal equations
- equations embedded in the story
- diagrams close to the relevant explanation
- interactive checkpoints
- selected original handwritten notes
- final mathematical chain

The presentation is inspired by the style and narrative structure of Andrej Karpathy's 2015 RNN post, not copied from its source code or text.

## Mathematical source

The Shazeer et al. paper is:

https://arxiv.org/abs/1701.06538

The article's Noisy Top-k equations follow Section 2.1. The CDF-based probability, smooth Load(X), and load loss follow Appendix A.

## Important wording note

The article preserves the explanatory flow of the handwritten notes and primarily changes grammar, notation, formatting, and mathematical clarity. Additional equations are inserted where they make the original reasoning explicit.
