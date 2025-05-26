devnotes:

may 26, 2025
repurposed an old commit from likelylogs so i have a clean nextjs project
git clone likelylogs into a new folder (freeflow), checkout the desired commit
`git branch -f main` to go from detached head to commited main (then checkout main)
fix the origin with `git remote remove origin` then add new freeflow repo in github ui
then `git remote add origin git@github.com:mlipman/freeflow.git` and `git push -u origin main` and that's about it

`npm run dev` to run dev
`npm run build` also important because that gets run before deploy.

todo: setup vercel project with auto-deploy on github push and cloudflare connection from mlipman.com/freeflow
