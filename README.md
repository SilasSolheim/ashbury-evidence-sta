# ASHBURY EVIDENCE STACK — GitHub Pages Deployment

## Quick Setup (5 minutes)

### Method 1: New Repository
1. Create new GitHub repository named `ashbury-evidence`
2. Upload `standalone-index.html` as `index.html`
3. Enable GitHub Pages (Settings → Pages → Deploy from branch → main)
4. Site will be available at: `https://[username].github.io/ashbury-evidence/`

### Method 2: Fork & Modify
1. Fork this repository
2. Rename `standalone-index.html` to `index.html`
3. Enable GitHub Pages
4. Customize content as needed

## Files Included

- `standalone-index.html` - Complete evidence stack (rename to `index.html`)
- `README-DEPLOYMENT.md` - This deployment guide
- `.nojekyll` - Bypass Jekyll processing (optional but recommended)

## Features

### Security & Protection
- ✅ Copy-paste protection
- ✅ Right-click disabled
- ✅ Text selection blocked
- ✅ Keyboard shortcuts disabled
- ✅ DevTools detection
- ✅ Print protection

### Design Elements
- ✅ Gothic evidence aesthetic
- ✅ Animated salt circles
- ✅ Marginalia annotations
- ✅ Evidence tape header
- ✅ Hoverable redacted text
- ✅ Mobile responsive
- ✅ Print optimized

### Evidence Pieces
- ✅ Case file cover sheet
- ✅ Journal fragments
- ✅ Recipe cipher
- ✅ Photo evidence placeholders
- ✅ Official documents
- ✅ Witness statements
- ✅ Laboratory reports

## Customization

### Adding Images
Replace placeholder image sections with:
```html
<img src="path/to/image.jpg" alt="Evidence description" class="evidence-image">
```

### Modifying Colors
Edit CSS variables in `:root` section:
```css
:root {
    --paper: #faf6e8;      /* Page background */
    --burn: #16130e;       /* Site background */
    --ink: #1a1611;        /* Main text */
    --blood: #6b2020;      /* Emphasis color */
    --catherine: #1e4d7b;  /* Catherine's notes */
    --margaret: #6b6256;   /* Margaret's notes */
    --voss: #2b4a4a;       /* Voss's notes */
    --stamp: #cfa14a;      /* Exhibit tabs */
}
```

### Adding Evidence
Follow this structure:
```html
<article class="evidence">
    <div class="exhibit-tab">EXHIBIT [LETTER]</div>
    <div class="evidence-body">
        <h2>Evidence Title</h2>
        <!-- Content here -->
        <div class="margin [character]">
            Annotation text
        </div>
    </div>
    <div class="page-num">00X</div>
</article>
```

## GitHub Pages Configuration

### Custom Domain (Optional)
1. Add `CNAME` file with your domain:
   ```
   evidence.yourdomain.com
   ```
2. Configure DNS CNAME record:
   ```
   Name: evidence
   Value: [username].github.io
   ```

### Force HTTPS
Enable "Enforce HTTPS" in repository Settings → Pages

### Branch Protection
- Deploy from `main` branch
- Use `/ (root)` folder
- Enable automatic deployment

## Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers

## Performance

- **Page Load**: < 2 seconds
- **Total Size**: ~26KB
- **Lighthouse Score**: 90+
- **Mobile Friendly**: Yes

## Security Notes

### Protection Features
- User selection disabled
- Right-click menu blocked
- Developer tools detection
- Keyboard shortcuts disabled
- Image drag prevention
- Copy/paste blocking

### Bypass Prevention
- Multiple protection layers
- JavaScript obfuscation
- CSS selection blocking
- Console warnings
- Security notifications

## Troubleshooting

### Page Not Loading
- Check repository is public
- Verify `index.html` exists in root
- Confirm GitHub Pages is enabled
- Wait 5-10 minutes for deployment

### Fonts Not Loading
- Ensure Google Fonts URL is correct
- Check browser console for errors
- Verify internet connection

### Mobile Issues
- Test responsive design
- Check viewport meta tag
- Validate CSS media queries

## Legal Considerations

### Content Protection
- This is demonstration code
- Not legally binding protection
- Consider additional measures for sensitive content
- Consult legal counsel for real evidence

### Copyright
- Modify content as needed
- Remove attribution if required
- Use original images only
- Respect fair use guidelines

## Support

### Common Issues
1. **Blank page**: Check console for JavaScript errors
2. **No styles**: Verify CSS is embedded correctly
3. **Images missing**: Use absolute or relative paths correctly
4. **Mobile problems**: Test on actual devices

### Debugging
- Use browser developer tools (when protection disabled)
- Check GitHub Pages build logs
- Validate HTML/CSS syntax
- Test in incognito mode

---

## Case Context (For Narrative Purposes)

**Subject**: The Divine Connection — recurring December 20 pattern in Ashbury  
**Investigator**: Gideon R. Voss (Contract)  
**Status**: Active Investigation

The pattern is older than the paperwork.

— G.R. Voss, 2024
