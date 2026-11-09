VIDHARTH® — PHONE UPLOAD EDITION

Is package mein sirf 2 zaroori files hain:
1) app.py  (poori website + animation + 4 photos isi ek file mein hain)
2) requirements.txt

PHONE SE GITHUB PAR UPDATE:
1. ZIP download karke phone ke File Manager mein Extract karo.
2. Chrome mein apna GitHub repository kholo.
3. Root folder mein app.py kholo. Pencil/Edit par tap karo, Select all karke extracted app.py ka poora code paste karo. Commit changes.
   Agar GitHub par file replace/upload option dikhe to extracted app.py upload karna aur purani app.py replace karna.
4. requirements.txt ko bhi isi tarah replace karo (Flask aur gunicorn dono hone chahiye).
5. Render dashboard kholo > apna Web Service > Manual Deploy > Deploy latest commit.
6. Deploy status Live hone par website refresh karo.

IMPORTANT:
- app.py aur requirements.txt repository ke ROOT mein hone chahiye.
- Is edition mein templates/static folders ki zaroorat nahi. Saari styling, animation aur photos app.py mein packed hain.
- ZIP file ko GitHub par upload mat karna; pehle extract karo.
- Render Build Command: pip install -r requirements.txt
- Render Start Command: gunicorn app:app

Aapka Instagram: https://www.instagram.com/vydh.03/
