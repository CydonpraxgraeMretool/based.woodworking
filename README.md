# Based Woodworking Website

This is a simple woodworking website where users can submit designs here for credit.
There are no ads, trackers or cookies (unless designs thereof).

This site is compiled and organized with Hugo, using [this very simple theme](https://github.com/lukesmithxyz/lugo).

## Ways to contribute

- By adding a design.
- Make a design and take a nice picture of it if no nice picture already
  exists. Submitted images should be small `.webp` files ideally less than 100K
  or so.
- Fix errors in designss or add minor improvements.

## Rules for submission

- Model submission files after [example.md](example.md). Put them in `content/`.
- File names should be the name of the design with words separated by hyphens
  (`-`). Not underscores, and definitely not spaces.
- Design must be "based." 
- Don't include an image unless (1) you took it yourself, and more importantly
  (2), **it actually looks good**! Most existing images on this site IMO look
  like ugly NEET photos, so you are welcome to take one a better one
  yourself and submit it if you make a design. If you don't know if your image is
  good, please have a real-live woman in real life approve your photo before
  you submit it. I'm serious about this, it's a waste for me to wade through
  disgusting photos in PRs.
- The file needs to be `\n` terminated in unix-fashion (if you're on Linux you
  don't need to care, it should be automatic).

**If you fail to do these things, I will close your submission and you will have to resubmit. I am tired of having to fix more than 50% of submissions.**

You may include a json file with your personal links/donation addresses in
`data/authors/your-name.json`. See mine (`data/authors/luke-smith.json`) for a
model. You can include: `website`, `donate` (general donation link), `email` or
crypto addresses as `btc`, `xmr` and `eth`.

### Tags

Remember to add tags to your design, but try to use tags already used by other design.

### Images

Images are stored in `/pix`.

Each design can have a title image at the top and perhaps several instructional
images as absolutely necessary.

Do not add stock images you found on the internet. Take a good picture yourself
of the actual design created. If you see a bad or substandard image, you may
submit a better one.

Images should be in `.webp` format and with as small file size as possible. If
you submit an image for say, `raised-bed.md`, it should be added as
`pix/raised-bed.webp`.

If you would like to add additional directional images,
they should be numbered with two digits like: `pix/raised-bed-01.webp`, etc.

Note also that images should have links beginning with a slash in this use
case, i.e. `/pix/...`.

## License

This website and all its content is in the public domain.
By submitting text or images or anything else to this repository,
you waive any pretense of ownership to it,
although you are welcome and recommended to give yourself credit
at the bottom of a submitted page for you adding it
(including personal or donation links).
