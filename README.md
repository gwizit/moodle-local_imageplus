# ImagePlus - Moodle Plugin
## Development Repository

**Plugin Name:** ImagePlus  
**Type:** Local Plugin (local_imageplus)  
**Developer:** G Wiz IT Solutions  
**Website:** https://gwizit.com  
**Version:** 3.0.7  
**License:** GNU GPL v3 or later

---

## 🎯 About This Plugin

ImagePlus is a powerful Moodle plugin that allows site administrators to search and replace files (images, PDFs, documents, videos, audio, archives) across their Moodle installation based on filename patterns. Features a user-friendly multi-step wizard interface with comprehensive security controls.

**Key Features:**
- 🔍 Smart search with wildcard support (`*` and `?`)
- 📁 Multi-file type support (images, PDFs, documents, videos, audio, archives)
- 🎯 Interactive file selection with checkboxes
- 🔐 Administrator-only access with multiple security layers
- 🎨 Automatic image format conversion and resizing
- 📊 Detailed operation logging and results
- ✅ GDPR compliant with Privacy API
- 🛡️ A+ Security Rating (see SECURITY_REVIEW.md)
- 🏗️ Modern architecture with Mustache templates, Output API, and ES6 modules

---

## 📋 Documentation

This repository contains comprehensive documentation:

- **[PLUGIN_CHECKLIST_REVIEW.md](PLUGIN_CHECKLIST_REVIEW.md)** - Moodle plugin checklist compliance review and submission guide
- **[SECURITY_REVIEW.md](SECURITY_REVIEW.md)** - Comprehensive security assessment (A+ rating)
- **[imageplus/README.md](imageplus/README.md)** - Complete user documentation and installation guide
- **[imageplus/TROUBLESHOOTING.md](imageplus/TROUBLESHOOTING.md)** - Common issues and solutions
- **[imageplus/COMPATIBILITY.md](imageplus/COMPATIBILITY.md)** - Moodle version compatibility guide

---

## 🚀 Quick Start

### Installation

**Method 1: Create ZIP and Upload (Recommended)**

1. **Create the package**:
   ```powershell
   .\create_package.ps1
   ```

2. **Upload to Moodle**:
   - Log in to Moodle as administrator
   - Go to Site administration → Plugins → Install plugins
   - Upload the created ZIP file
   - **If prompted "Unable to detect the plugin type":**
     - Select **"Local plugin (local)"** from the dropdown
     - Verify the plugin folder name is **"imageplus"**
     - Click "Install plugin from the ZIP file"
   - Follow the installation wizard

3. **Clear caches** (Important!):
   - Go to Site administration → Development → Purge all caches
   - Or run: `php admin/cli/purge_caches.php`

**Method 2: Manual Installation**

1. Copy the `imageplus` folder to `[moodle-root]/local/`
2. Visit Site administration → Notifications
3. Follow the installation wizard
4. Clear all caches

For detailed installation instructions, see [imageplus/README.md](imageplus/README.md).

---

## 🔗 Links

- **Source Code:** https://github.com/gwizit/moodle-local_imageplus
- **Bug Tracker:** https://github.com/gwizit/moodle-local_imageplus/issues
- **Support / Issues:** https://github.com/gwizit/moodle-local_imageplus/issues
- **Developer Website:** https://gwizit.com
- **Moodle Plugins Directory:** *(pending submission)*

---

## ✅ Plugin Status

**Current Status:** ✅ **Ready for Submission**

- ✅ All critical issues fixed
- ✅ Security guidelines fully compliant (A+ rating)
- ✅ Privacy API implemented
- ✅ GitHub Issues tracker active
- ✅ Comprehensive documentation
- ✅ Moodle 4.3 - 5.1+ compatible
- ✅ Modern architecture with proper template separation
- ✅ Repository follows naming convention: `moodle-local_imageplus`

See [PLUGIN_CHECKLIST_REVIEW.md](PLUGIN_CHECKLIST_REVIEW.md) for detailed compliance status.

---

## 📦 What's Included

Complete Moodle plugin with:
- ✅ Multi-step wizard interface
- ✅ File system & database search
- ✅ Auto format conversion & resizing (with GD library)
- ✅ Safe preview mode
- ✅ Interactive file selection
- ✅ Comprehensive security controls
- ✅ Complete documentation
- ✅ GDPR compliance
- ✅ Privacy API implementation
- ✅ Events API logging
- ✅ A+ Security implementation

---

## 🛡️ Security

ImagePlus has been thoroughly reviewed and achieves an **A+ security rating**:

- ✅ Site administrator-only access
- ✅ Multiple permission layers
- ✅ XSS protection throughout
- ✅ CSRF protection on all actions
- ✅ SQL injection prevention
- ✅ Directory traversal prevention
- ✅ File type validation
- ✅ Input sanitization
- ✅ Output escaping

See [SECURITY_REVIEW.md](SECURITY_REVIEW.md) for complete security assessment.

---

## 📝 Requirements

### Moodle Requirements
- **Moodle version:** 4.3 to 5.1+ (fully tested)
- **PHP version:** 7.4 or higher (8.0+ recommended)

### PHP Extensions
- **Required:** mbstring, mysqli/pgsql, json
- **Optional:** GD library (for image cross-format conversion and resizing)

### Server Requirements
- Write permissions to Moodle's `dataroot/filedir` directory
- Sufficient PHP memory limit (128MB minimum, 256MB+ recommended)

See [imageplus/COMPATIBILITY.md](imageplus/COMPATIBILITY.md) for detailed compatibility information.

---

## 🤝 Contributing

Contributions are welcome!

- **Report bugs:** https://github.com/gwizit/moodle-local_imageplus/issues
- **Submit pull requests:** https://github.com/gwizit/moodle-local_imageplus
- **Contact us:** Through https://gwizit.com

Please follow Moodle coding standards when contributing.

---

## 📄 License

This plugin is licensed under the [GNU GPL v3 or later](LICENSE).

---

## 💝 Support

**Found this plugin useful?** Consider supporting its development!

- **Donate:** https://square.link/u/DMRTvZ0Y
- **Report issues:** https://github.com/gwizit/moodle-local_imageplus/issues
- **Professional support:** Contact via https://gwizit.com

---

## 🏆 Credits

**Developed by:** [G Wiz IT Solutions](https://gwizit.com)  
**Copyright:** 2025 G Wiz IT Solutions  
**License:** GNU GPL v3 or later

---

**Thank you for using ImagePlus!** 🎓
