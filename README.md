# wiki-test

Test creating a wiki on github.

- main page> wiki > create new page

================================

Plus test github pages (repo/settings/pages)

This appears here: https://michaelbrownid.github.io/wiki-test/

Here is a link to another file: [foo.html](foo.html)

Another link : [foo.md](foo.md)

Data: [foo.dat](foo.dat). Note files greater than 50MB will get a
warning. 100MB will be blocked. Total repo sizes should be less than
1GB and 5GB is strongly recommended.

What: [bar.md](bar.md)

RESULT: WEIRD!!!! Github pages automatically translates foo.md into
foo.html to be displayed. HOWEVER, because foo.html already exists, it
does not overwrite it and the link for "foo.md" goes to "foo.html"
which is NOT the markdown but the original html. RULE: don't have html
files with the same basename as markdown files.

================================

![image1](happy.jpeg)

[image2Link](blue.jpeg)

[sampleZip](sample-1.zip)

================================
