# Hollow House Institute  


#!/usr/bin/env bash

echo "=== Creating Hollow House Standards Library local repo ==="

TARGET="/c/Users/amy/Documents/Hollow_House/hollowhouse_Hollow_House_Standards_Library"

mkdir -p "$TARGET"
cd "$TARGET" || { echo "❌ Folder not found: $TARGET"; exit 1; }

mkdir -p docs
mkdir -p legal
mkdir -p assets/diagrams
mkdir -p projects

cat > README.md << 'EOF'
# Hollow House Standards Library  
Ethical AI • Research Standards • Certification Criteria  
**Hollow House Institute**

This repository holds the ethical standards, certification frameworks, and governance documentation for the Hollow House Institute.
