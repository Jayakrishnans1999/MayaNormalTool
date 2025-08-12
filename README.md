# MayaNormalTool
Over the years, I’ve often seen talented 3D artists losing precious hours fixing inverted normals — a small but frustrating issue that can derail project timelines. Whether you’re preparing assets for real-time rendering or baked workflows, these fixes shouldn’t be a bottleneck.
So, I built Normal Flipper Tool for Maya 🛠️:
 ✅ Smart Detection – Only flips the faces that are actually inverted
 ✅ Works with complex meshes, groups, and components
 ✅ Quick UI for one-click fixes
 ✅ Safe and undo-friendly
This tool is designed not just for my team but for any artist struggling to meet deadlines while maintaining top-quality models.
💡 My goal is simple: eliminate repetitive technical hurdles so artists can focus on creativity.

# Instructions for use:
"""
HOW TO USE THIS TOOL IN MAYA 2026:

1. Copy this entire script
2. Open Maya's Script Editor (Windows > General Editors > Script Editor)
3. Paste the code in the Python tab
4. Execute the script (Ctrl+Enter or press Execute button)

This will open a UI window with the following options:
- "Flip Normals (Inside → Outside)": Main function to flip selected mesh normals
- "Toggle Normal Display": Shows/hides face normals in viewport for visualization

WORKFLOW:
1. Select your mesh object(s) in the viewport
2. Run the script to open the UI
3. Click "Toggle Normal Display" to see current normal directions
4. Click "Flip Normals" to reverse them
5. Check the result in the viewport

The tool also includes additional functions:
- flip_normals_conform_to_adjacent(): For mixed normal directions
- average_normals(): For smooth shading

You can also add this script to your shelf or create a custom button for quick access.
"""

