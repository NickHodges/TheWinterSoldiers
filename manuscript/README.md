# The Winter Soldiers - Leanpub Manuscript

This manuscript is ready for publishing on Leanpub.

## Directory Structure

```
manuscript/
├── Book.txt              # Main book file list (defines book structure)
├── Sample.txt            # Sample/preview file list (Prologue + first 3 chapters)
├── frontmatter.txt       # Marks beginning of front matter
├── prologue.md           # Prologue
├── mainmatter.txt        # Marks beginning of main content
├── chapter-01.md         # Chapter 1
├── chapter-02.md         # Chapter 2
│   ...                   # Chapters 3-20
├── chapter-21.md         # Chapter 21
├── backmatter.txt        # Marks beginning of back matter
├── epilogue.md           # Epilogue
├── AboutTheAuthor.md     # About the author section
├── images/               # Place images here
└── resources/            # Additional resources
```

## Book Content

**Front Matter:**
- Prologue (displayed with Roman numerals in TOC)

**Main Content:**
- 21 Chapters (displayed with Arabic numerals 1-21 in TOC)

**Back Matter:**
- Epilogue
- About the Author

**Sample/Preview:**
- Includes: Prologue and Chapters 1-3

## How to Publish on Leanpub

### Option 1: Dropbox Mode
1. Create a Leanpub account at https://leanpub.com
2. Create a new book
3. Choose "Dropbox" as your writing mode
4. Copy the entire `manuscript/` folder to your Leanpub Dropbox folder
5. Click "Preview" or "Publish" on Leanpub

### Option 2: GitHub Mode
1. Create a GitHub repository
2. Push this `manuscript/` folder to your repository
3. Connect your Leanpub book to the GitHub repository
4. Click "Preview" or "Publish" on Leanpub

### Option 3: Upload Mode
1. Zip the entire `manuscript/` folder
2. Upload to Leanpub via their web interface

## File Format

All files are in **Leanpub Flavored Markdown (LFM)**:
- Chapter headings use `#` (creates new chapters)
- Sections use `##`
- Subsections use `###`
- Italics: `*text*`
- Bold: `**text**`

## Images

The `AboutTheAuthor.md` file references `ajhighcontrast.jpg`. Make sure to:
1. Place this image in the `manuscript/images/` folder
2. Update the reference if needed to: `![](images/ajhighcontrast.jpg)`

## Next Steps

1. ✅ Manuscript is converted and ready
2. Add book cover image (optional):
   - Create `title_page.jpg` or `title_page.png` (2550x3300 pixels)
   - Place in `manuscript/images/` folder
3. Add author photo to `manuscript/images/` folder if not already there
4. Choose your Leanpub publishing mode and upload
5. Preview your book on Leanpub
6. Publish!

## Resources

- [Leanpub Manual](https://leanpub.com/manual/read)
- [Leanpub Flavored Markdown Manual](https://leanpub.com/lfm/read)
- [Markua Manual](https://leanpub.com/markua/read) (newer format option)

## Notes

- Original text files are in the parent directory (backed up in `.backup_original/`)
- All text has been cleaned of old word processor artifacts
- Unix line endings used throughout
- UTF-8 encoding
