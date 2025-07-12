---
title: "Technical Details"
---

## Recent Updates

### 2025-07-12: v1.0.0 Release (🔄 Awaiting Chrome Web Store Approval)
✅ **Fixed**: Chrome compatibility issues resolved with complete AI system rebuild
- Completely migrated to Chrome's native AI LanguageModel API
- Enhanced error handling and user feedback
- Improved bookmark categorization accuracy
- Better performance and reliability across Chrome versions

**Status**: Submitted to Chrome Web Store on 2025-07-12, currently awaiting approval. Expected approval time: 1-5 business days.

### 2025-07-10: Chrome Update Compatibility Issue
✅ **Resolved**: "AI features are not supported in your browser" error message
- **Issue**: After Chrome updates, users saw the error: "AI features are not supported in your browser. However, you can still tag this bookmark manually using autocomplete."
- **Root Cause**: Chrome's transition from Origin Trial to stable AI API
- **Solution**: Complete migration to Chrome's native LanguageModel API in v1.0.0
- **Status**: Fixed and included in the v1.0.0 release awaiting approval

**Note**: The v1.0.0 update is not yet available in the Chrome Web Store. Users will receive the update automatically once approved by Google.

## System Requirements

### Chrome Version
- **Minimum**: Chrome 138 or higher
- **Recommended**: Latest Chrome version

**Important**: TagChoose will not work on Chrome versions below 138. The AI features require Chrome's stable Prompt API, which was introduced in Chrome 138.

### Hardware Requirements
Please refer to the [official Chrome AI requirements](https://developer.chrome.com/docs/extensions/ai/prompt-api) for detailed specifications:

- **Operating system**: Windows 10 or 11; macOS 13+ (Ventura and onwards); or Linux
- **Storage**: At least 22 GB on the volume that contains your Chrome profile
- **GPU**: Strictly more than 4 GB of VRAM
- **Network**: Unlimited data or an unmetered connection

**Note**: Chrome for Android, iOS, and ChromeOS are not yet supported by the AI APIs.

## Chrome Setup

**No setup required!** As of Chrome 138, TagChoose works out of the box without any experimental flags.

### For Chrome Versions Below 138
TagChoose is not compatible with Chrome versions below 138. Please update to Chrome 138 or higher to use the AI features.

## Troubleshooting

### AI Features Not Working
1. **Check Chrome version**: Ensure you're using Chrome 138 or higher
2. **Verify hardware requirements**: Check the [official requirements](https://developer.chrome.com/docs/extensions/ai/prompt-api)
3. **Check storage space**: Ensure at least 22 GB free space on your Chrome profile volume
4. **Verify GPU**: Ensure you have more than 4 GB of VRAM
5. **Check network**: Ensure you have an unmetered connection for initial model download

### Chrome Version Issues
If you're using Chrome below version 138:
- **Update Chrome** to version 138 or higher
- **No workaround available** - the AI features require Chrome's stable Prompt API
- **Manual bookmarking** will still work, but AI categorization will be unavailable
