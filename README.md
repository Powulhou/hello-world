 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index f1ec81d2b7bf8c5d16f32a31dc3dc0430a0053eb..ebbde3bb43d84e0047ee7b2ef1d63fe95c4b3c12 100644
--- a/README.md
+++ b/README.md
@@ -1,4 +1,21 @@
 
+# Paradox Orchard
+
+Paradox Orchard is a brand-new browser game prototype where you grow fruit echoes across three timelines:
+
+- **Past**
+- **Present**
+- **Future**
+
+You score by creating **Paradox Blooms** (the same fruit on the same row in all three timelines).
+Each anchor increases entropy; blooms reduce it. Reach 100% entropy and the run ends.
+
+## Controls
+
+- `A` / `←`: Move active fruit left
+- `D` / `→`: Move active fruit right
+- `S` / `↓`: Speed up descent by one tick
+- `Space`: Anchor the fruit immediately
+
+## Run locally
+
+Because this is plain HTML/CSS/JS, you can run it by opening `index.html` in your browser.
 
EOF
)
