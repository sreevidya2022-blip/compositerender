# CompositeLab - ML Property Predictor (Render)

Deploys in 2 clicks on Render with no manual configuration needed!

## ✨ Features

- Forward prediction: Input composition → Get properties
- Inverse prediction: Input properties → Get optimal composition
- AI chat with Groq Llama 3.3 70B
- Real-time charts with uncertainty bands
- Error landscape heatmap
- Buckling strength prediction (500-1200 N/m)

## 🚀 Deploy in 2 Clicks

### Step 1: Connect GitHub
1. Go to render.com
2. Click "New +"
3. Select "Web Service"
4. Connect your GitHub repo
5. Render reads render.yaml automatically

### Step 2: Add API Key
1. During deployment, set environment variable:
   - Key: `GROQ_API_KEY`
   - Value: Your key from console.groq.com
2. Click "Deploy"
3. Done! ✅

## 📋 What's Included

- `app.py` - Flask backend (ready to go)
- `ml_model.py` - ML engine (ready to go)
- `index.html` - Web UI (ready to go)
- `app.js` - Frontend logic (ready to go)
- `style.css` - Styling (ready to go)
- `render.yaml` - Render config (automatic)
- `requirements.txt` - Dependencies (automatic)

## 🔑 Get Groq API Key

1. Visit console.groq.com
2. Sign up (free)
3. Create API key
4. Copy key (starts with `gsk_`)
5. Paste into Render environment variables

## 📊 How to Use

1. Visit your live Render URL
2. Upload 3 Excel files (Theory, FEA, Experimental)
3. Click "Train Models"
4. Use sliders to set BN% and AO%
5. Click "Predict Properties"
6. See all predictions including Buckling
7. Use AI chat to ask questions
8. Try inverse optimization
9. View error heatmap

## ⏱️ Deployment Time

- GitHub connection: 1 minute
- Render detection: Automatic (reads render.yaml)
- Build: 2-3 minutes
- Deploy: Instant
- **Total: ~5 minutes** ✅

## 🔗 Render Links

Dashboard: https://dashboard.render.com
Docs: https://render.com/docs

## ✅ What Works

✅ Forward prediction
✅ Inverse optimization  
✅ Charts & visualization
✅ AI chat (Groq)
✅ File upload & training
✅ Heatmap display
✅ All 4 properties (including Buckling)

## 📱 Share Your URL

After deployment:
```
Your app URL: https://your-app-name.onrender.com
Share it! Everyone can use it.
```

## 🎓 Tech Stack

- Backend: Flask + scikit-learn
- Frontend: Vanilla JS + Chart.js
- AI: Groq Llama 3.3 70B
- Deploy: Render

## 💡 Notes

- Models train per session
- Uploaded files temporary
- Free tier suitable for demos
- Auto-deploys from GitHub

---

**Status:** ✅ Production Ready
**Deploy Time:** ~5 minutes
**Setup Required:** NO - Fully automated
**Clicks Needed:** Just 2!

That's it! 🚀
