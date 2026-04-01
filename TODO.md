# Netlify Deploy Fix - Git Setup Plan

## Status: .gitignore created ✓ | Waiting Git install

**1. [x] Create .gitignore** ✓
**2. [ ] Install Git** 
   - https://git-scm.com/download/win
   - Run `git --version` → reply output

**3. [ ] Init & First Commit**
   ```
   git init
   git add .
   git commit -m "Initial commit: Vite portfolio"
   ```

**4. [ ] Push to main**
   ```
   git branch -M main
   git remote add origin https://github.com/Huy140-qa/hwii-cv.git
   git push -u origin main
   ```

**5. [ ] Netlify: Set branch=main, trigger deploy**
   - Build: `npm run build`
   - Publish: `dist`

**Next: User runs Git install + `git --version`**


