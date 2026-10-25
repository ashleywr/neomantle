# Neo Mantle

An unofficial **Minecraft 1.21.1 NeoForge** port of **Mantle** by SlimeKnights.

Neo Mantle is a library/dependency mod & is **required by [Neo Tinkers](https://github.com/vancevoj/neotinkers)** and does little on its own.

Full credit for the mod goes to SlimeKnights. I take no credit for any of the original work. . This project is **not official** and is in no way endorsed by or affiliated with SlimeKnights. Use it at your own discretion.

## Download

- [Neo Mantle - latest release](https://github.com/vancevoj/neomantle/releases/latest)

## Optional Download - Neo Planner

Neo Planner is another **unofficial** port of the Tinkers Construct Planner addon-mod, a client-side helper for trying out tool material & modifier combinations. This port is functional for 1.21.1 NeoForge, requires Neo Tinkers, and again - is in no way endorsed by any persons aside myself. Download & use the following at your own discretion.

- [Neo Planner - latest release](https://github.com/vancevoj/neoplanner/releases/latest)

<!-- ashley-release-information -->

## Ashley's builds

This is an unofficial maintenance fork. Original authors retain ownership and credit. See the [upstream project](https://github.com/vancevoj/neomantle) for the original mod. Local changes do not imply upstream endorsement.

Licensing: **MIT**. Existing license files, copyright notices, attribution and any separate asset terms remain in force. This fork does not relicense upstream work.

Provided **AS IS**, without warranty of any kind. Maintenance, updates and support are best effort; compatibility with every modpack is not guaranteed.

### Downloads and installation

Download a runtime `.jar` from [GitHub Releases](https://github.com/ashleywr/neomantle/releases). Use the Minecraft version and loader named in that release and install its required dependencies. Do not install `-sources`, `-dev`, `-slim`, `-common` or test JARs as the mod.

Close Minecraft, back up your world, and place the matching runtime JAR in the instance's `mods/` directory. Replace older versions of this same mod rather than loading duplicates. For content mods, install matching versions on the server and its clients unless the release explicitly says client-only or server-only.

### Building and reporting problems

Use Java 21 and the checked-in Gradle wrapper:

```powershell
.\gradlew.bat build
```

Build outputs are under `build/libs/` or each loader subproject's `build/libs/`. Some projects require the local development dependencies described above; those dependencies are not included in the download.

For a problem report, include the exact release filename, Minecraft and loader versions, relevant mod versions, `logs/latest.log`, and a crash report if one was written. Remove private information before sharing logs. Remove the JAR to uninstall; worlds containing this mod's blocks, entities or world generation may require restoring a backup.
