---
layout: post
title:  "How to write a Blog Post"
date:   2020-02-01 17:00:00 +0000
categories: jekyll update
---

The aim of this post is to give simple instructions on how to write a blog
post for this web site.  Mostly because the instructions I could find where
all wrong in some respect!

1. Navigate to
   [https://github.com/gretton-dann/gretton-dann.github.io/tree/master/_posts](https://github.com/gretton-dann/gretton-dann.github.io/tree/master/_posts)

2. Click 'Create new file'

3. In the box title "Name your file..." put in a file name in the following
   format:  `YYYY-MM-DD-hyphen-separeted-title.markdown`.  See other files in
   that directory for examples.  Don't use spaces in the filename.

4. In the large text box add the following:

```yaml
---
layout: post
title:  "TITLE"
date:   YYYY-MM-DD HH:MM:SS +0000
categories: CAT-1 CAT-2
---
```

Where:

 * **TITLE**: Should be the blog title
 * **YYYY-MM-DD HH:MM:SS**: Should be the current date
 * **CAT-#**: Are category names.  You can make these up!

5. Under that enter your blog post.  The text is in Markdown format.
   Instructions here: https://guides.github.com/features/mastering-markdown/

6. In the box 'Commit new file' enter a short title for the commit.  "Add blog
   post for YYYY-MM-DD" is fine.  Also add a longer description if you feel it
   is necessary.

7. Ensure "Commit directly to the master branch" is selected.
   (Yes this is extremely bad practice - but I did say "simple").

8. Click the green "Commit new file" button.

