#custom, static site generator
by [yasha mostofi](http://www.yashamostofi.com/)

after I'm done building this, I'll publish a huge blog post detailing the process.

## _specs (apr 13)_
workflow:
- configure blog using `config.json` type structure
- set global variables in `config.json` 
- write in markdown
- define variables at top of file
- run python script
- script dumps out html files for use

variable examples:
- `post_image` title and button background for post
- `date`
- `time`
- `author` (support for multiple authors...?)
- `post_title`
- `post_leading_text` for something to _captivate_ your audience
- `post_desc` short blurb about the post

**todo**
- figure out a way to parse for variables
- maybe use go instead of python?

## _specs (apr 8)_
- python
- markdown
- **lots** of customization
