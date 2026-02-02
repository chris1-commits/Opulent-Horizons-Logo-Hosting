# Contributing to Opulent Horizons Image Hosting

Thank you for contributing to our image hosting repository! Please follow these guidelines to maintain organization and quality.

## 📝 Guidelines for Adding Images

### 1. Choose the Right Category

Place your image in the appropriate directory:

- **logos/** - Company logos, product logos, brand marks
- **photos/** - Photographs, product images, team photos
- **icons/** - UI icons, small graphics, symbols
- **banners/** - Website banners, email headers, promotional graphics
- **backgrounds/** - Background images, patterns, textures
- **avatars/** - User profile pictures, default avatars

### 2. Naming Convention

Follow these rules when naming your files:

✅ **DO:**
- Use lowercase letters only
- Separate words with hyphens (`-`)
- Be descriptive and specific
- Include dimensions for size-specific images
- Use standard file extensions

✅ **Examples:**
```
company-logo.png
team-photo-2024.jpg
hero-banner-1920x1080.jpg
search-icon.svg
user-avatar-default.png
```

❌ **DON'T:**
- Use spaces in filenames
- Use special characters (except hyphens)
- Use generic names like `image1.png`
- Use uppercase letters

### 3. Image Optimization

Before uploading, optimize your images:

**Tools:**
- [TinyPNG](https://tinypng.com/) - PNG/JPG compression
- [SVGO](https://github.com/svg/svgo) - SVG optimization
- [ImageOptim](https://imageoptim.com/) - Mac image optimizer
- [Squoosh](https://squoosh.app/) - Web-based image optimizer

**Guidelines:**
- Compress images without visible quality loss
- Remove unnecessary metadata
- Use appropriate dimensions (don't upload oversized images)
- Consider using WebP format for better compression

### 4. File Formats

Choose the right format for your image:

| Format | Best For | When to Use |
|--------|----------|-------------|
| PNG | Logos, icons, transparency | When you need transparency or crisp edges |
| JPG | Photos, complex images | For photographs and images with many colors |
| SVG | Scalable graphics | For logos and icons that need to scale |
| GIF | Simple animations | For small, simple animated graphics |
| WebP | Modern web images | For better compression (when browser support allows) |

### 5. Image Dimensions

Common dimension guidelines:

**Logos:**
- Small: 200x200px or smaller
- Medium: 400x400px
- Large: 800x800px or larger

**Banners:**
- Desktop: 1920x400px to 1920x600px
- Mobile: 750x400px to 750x600px
- Email: 600x200px to 600x400px

**Icons:**
- Small: 16x16px, 24x24px, 32x32px
- Large: 64x64px, 128x128px, 256x256px

**Photos:**
- Thumbnail: 300x300px
- Medium: 800x600px or 1024x768px
- Large: 1920x1080px or higher

### 6. Commit Messages

Use clear, descriptive commit messages:

✅ **Good:**
```
Add company logo in PNG and SVG formats
Update team photo for 2024
Replace outdated product banner
```

❌ **Bad:**
```
Update image
Add files
Changes
```

### 7. File Size Limits

Try to keep file sizes reasonable:

- **Icons:** < 50KB
- **Logos:** < 200KB
- **Photos:** < 500KB
- **Banners:** < 500KB
- **Backgrounds:** < 300KB

If your image is larger, consider:
- Further compression
- Reducing dimensions
- Converting to a more efficient format

### 8. Updating Existing Images

When replacing an image:

1. **If it's a new version:** Add a version suffix (e.g., `logo-v2.png`)
2. **If it's a replacement:** You can overwrite the old file, but note the change in your commit message
3. Update any documentation that references the image

### 9. Image Catalog

After adding significant images, consider updating the `IMAGE_CATALOG.md` file to help others discover your additions.

## 🔍 Quality Checklist

Before committing, verify:

- [ ] Image is in the correct category folder
- [ ] Filename follows naming conventions (lowercase, hyphens, descriptive)
- [ ] Image is optimized and compressed
- [ ] File format is appropriate for the image type
- [ ] Dimensions are reasonable for the intended use
- [ ] File size is within recommended limits
- [ ] Commit message is clear and descriptive
- [ ] Image displays correctly when accessed via raw URL

## 🚫 What Not to Upload

- Personal or sensitive information
- Copyrighted material you don't have rights to use
- Excessively large or unoptimized files
- Images containing customer data
- Temporary or test files

## ❓ Questions?

If you're unsure about anything, please:
- Review the main [README.md](README.md)
- Check the category-specific README in each folder
- Ask the repository maintainers

## 📋 Example Workflow

```bash
# 1. Add your optimized image to the appropriate folder
cp my-logo.png images/logos/company-logo.png

# 2. Stage the file
git add images/logos/company-logo.png

# 3. Commit with a descriptive message
git commit -m "Add company logo in PNG format"

# 4. Push to the repository
git push
```

Thank you for helping maintain a well-organized image hosting repository!
