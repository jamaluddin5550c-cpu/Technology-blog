# Technology-blog
# clone your repo (use HTTPS or SSH)
git clone git@github.com:jamaluddin5550c-cpu/Technology-blog.git
cd Technology-blog

# create folders and copy your articles in (adjust source path)
mkdir -p posts assets
cp /path/to/my/articles/*.md posts/

# add, commit, push
git add .
git commit -m "Backup: add articles"
git push origin main
