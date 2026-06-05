# Vercel Deployment Instructions

## Option 1: Using Vercel CLI (Terminal e run koro)

```bash
vercel --prod
```

Terminal e questions ashbe:
1. "Set up and deploy?" → Type: **Y** and press Enter
2. "Which scope?" → Select your account
3. "Link to existing project?" → Type: **N** 
4. "What's your project's name?" → Press Enter (default: TravelWebsite)
5. "In which directory is your code located?" → Press Enter (default: ./)

Deployment complete! URL pabe terminal e.

---

## Option 2: Using Vercel Dashboard (Easiest!)

1. Go to: https://vercel.com/new
2. Click "Continue with GitHub" or "Import Git Repository"
3. OR simply drag and drop the entire **TravelWebsite** folder
4. Vercel automatically deploy korbe
5. Live URL pabe!

---

## Option 3: Quick Command (If already logged in)

```bash
cd C:\Website\TravelWebsite
vercel --yes --prod
```

This will skip all questions and directly deploy!

---

## Files Ready for Deployment:
✅ index.html (main website)
✅ images/ folder (19 Iceland images)
✅ vercel.json (config file)
✅ Git initialized and committed

---

## After Deployment:
Your website will be live at: `https://tm-travel-website-xxxxx.vercel.app`

Share the URL anywhere! 🚀
