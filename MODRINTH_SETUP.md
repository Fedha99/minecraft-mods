# Modrinth Setup Guide for BetterRPGFantasy

## Directory Structure

After organizing files, your repo should look like:

```
minecraft-mods/
├── mods/                          # All mod JAR files here
│   ├── create-1.20.1-6.0.8.jar
│   ├── irons_spellbooks-1.20.1-3.16.3.jar
│   ├── epic-fight-20.14.17-mc1.20.1-forge.jar
│   └── ... (140+ more mods)
├── modrinth.index.toml           # Modpack manifest
├── README.md                     # Modpack documentation
├── MODLIST.md                    # This file
└── pack.png                      # Cover image (optional)
```

## Upload Steps to Modrinth

### 1. Create Modrinth Account
- Go to [modrinth.com](https://modrinth.com)
- Sign up and verify email

### 2. Create New Project
- Click "Create" → Select "Modpack"
- Fill in details:
  - **Name:** BetterRPGFantasy Modpack
  - **Summary:** A RPG-Adventure modpack with dragons, leveling, and optimized for low-end devices
  - **Description:** Use README.md content
  - **Categories:** `Adventure`, `RPG`, `Combat`
  - **License:** Choose one (e.g., All Rights Reserved)

### 3. Upload Files
- Generate `.mrpack` format:
  1. Create ZIP with this structure:
     ```
     overrides/
     └── mods/
         └── (all .jar files)
     modrinth.index.toml
     ```
  2. Upload to Modrinth
  3. Set version to `1.0.0`
  4. Set game version: `1.20.1`
  5. Set loader: `Forge`

### 4. Submit for Review
- Click "Publish"
- Wait for Modrinth moderation (usually 1-2 days)

---

## Quick Checklist

- [ ] Modrinth account created
- [ ] Project metadata filled
- [ ] Cover image added (recommended)
- [ ] README content reviewed
- [ ] All mods tested for compatibility
- [ ] Files organized in mods/ folder
- [ ] modrinth.index.toml updated
- [ ] .mrpack file created
- [ ] Submitted to Modrinth

---

## Tips

✅ Make sure all mods are from reputable sources
✅ Include mod credits in README
✅ Test modpack before submission
✅ Provide clear installation instructions
✅ Update regularly with new versions

---

For more info, check [Modrinth Documentation](https://docs.modrinth.com/docs/publish/modpack/)
