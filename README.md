## .gitignore for Unity

cache delete and apply commands

```
git rm -r --cached .
git add .
git commit -m "Apply .gitignore"
```

---------------------------------------------------
.gitignore
```

### Unity ###
# .gitignore file must be placed at the root of your Unity project directory

/[Ll]ibrary/
/[Tt]emp/
/[Oo]bj/
/[Bb]uild/
/[Bb]uilds/
/[Ll]ogs/
/[Uu]ser[Ss]ettings/

# MemoryCaptures
/[Mm]emoryCaptures/

# Asset .meta files
!/[Aa]ssets/**/*.meta

# You can comment out this line if you want to ignore "AssetStore tools plugin"
/[Aa]ssets/AssetStoreTools*

# Jetbrains Rider plugin
/[Aa]ssets/Plugins/Editor/JetBrains*

# Visual Studio hidden cache
.vs/

# Gradle hidden cache
.gradle/

# ALL solution and project files
ExportedObj/
.consulo/
*.csproj
*.unityproj
*.sln
*.suo
*.tmp
*.user
*.userprefs
*.pidb
*.booproj
*.svd
*.pdb
*.mdb
*.opendb
*.VC.db

# Unity meta files
*.pidb.meta
*.pdb.meta
*.mdb.meta

# Unity crash reports
sysinfo.txt

# Builds
*.apk
*.aab
*.unitypackage

# Crashlytics
crashlytics-build.properties

# Packed
/[Aa]ssets/[Aa]ddressable[Aa]ssets[Dd]ata/*/*.bin*

# Android Assets
/[Aa]ssets/[Ss]treamingAssets/aa.meta
/[Aa]ssets/[Ss]treamingAssets/aa/*

# OS generated (macOS or Windows)
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
Icon?
ehthumbs.db
Thumbs.db

# EOF

```
