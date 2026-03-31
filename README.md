# AVYA Pure Living — Website

## Folder structure
```
avya-site/
├── index.html          ← main page (edit this for content changes)
├── images/
│   ├── logo.jpg        ← replace with new logo version anytime
│   ├── bath/           ← bath product photos
│   │   ├── bath-153.jpg   (Bamboo Body Brush)
│   │   ├── bath-062.jpg   (Beechwood Body Brush)
│   │   ├── bath-1099.jpg  (Long Handle Brush)
│   │   ├── bath-126.jpg   (Massage Brush)
│   │   ├── bath-086.jpg   (Large Body Brush)
│   │   ├── bath-zj-72.jpg (Loofah Handle Brush)
│   │   ├── bath-685.jpg   (Facial Brush A)
│   │   └── bath-686.jpg   (Facial Brush B)
│   └── bags/           ← bag product photos
│       ├── bag-evil-eye-tote.jpg
│       ├── bag-jaipuri-handcraft.jpg
│       ├── bag-summer-cotton-tote.jpg
│       ├── bag-print-cotton-tote.jpg
│       ├── bag-office-tote.jpg
│       ├── bag-macrame-sling.jpg
│       ├── bag-owl-tote.jpg
│       └── bag-hemp-pouch.jpg
└── README.md
```

## How to update images
1. Replace any image file in the images/ folder with a new photo
2. Keep the SAME filename
3. Commit and push to GitHub → site updates automatically

## How to update product prices or text
1. Open index.html in any text editor
2. Search for the product name (e.g. "Bamboo Body Brush")
3. Edit the price or description directly
4. Commit and push to GitHub

## Deploying on GitHub Pages
1. Create a new repo on github.com named: avya-organic-site
2. Upload this entire folder
3. Go to repo Settings → Pages → Source: main branch / root
4. Add your custom domain: avyaorganic.com
5. Update DNS: CNAME record pointing avyaorganic.com → YOUR-USERNAME.github.io

## Adding a new product
Copy any product card block in index.html:
```html
<div class="pcard">
  <div class="pimg-wrap">
    <img src="images/bath/NEW-PHOTO.jpg" alt="Product Name" class="pimg">
    <div class="pquick">Shop on Shopee →</div>
  </div>
  <div class="pcat">Category</div>
  <div class="pname">Product Name</div>
  <div class="pdesc">Short description</div>
  <div class="pprice">XXX,000 ₫</div>
</div>
```
