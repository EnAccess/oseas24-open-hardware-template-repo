<p align="center">
  <a href="https://github.com/EnAccess/OpenSmartMeter">
    <img
      src="https://drive.google.com/uc?id=1gtL_p7l3HbOcCzc09A7KW5d7B5qn-BDs"
      alt="OpenSmartMeter"
      width="640"
    >
  </a>
</p>
<p align="center">
    9-10 May | Open Source in Energy Access Symposium Hackathon
</p>

---

## Open Hardware Template Repository

**Stack:** KiCAD, Python scripting

**Helpful experiences:** KiCAD automation, CI/CD pipelines

**Abstract:** The tooling for Open Hardware repositories is currently undergoing rapid development. It can be overwhelming for an electrical engineer working on the PCB’s to follow up on all this.

## Challenge

The goal of this workgroup is to create a KiCAD template repository with the some of following features (in no particular order)

- Automatic diff generation for PCB’s and Schematics
- KiCanvas WebViewer Link integration
- CI pipeline to run lint checks: DRC rules check, conventions, etc..
- Release management, using GitHub tags
- Workflow to update the release tag as labels on the PCB
- Deploy workflow that generates production files and makes them available in the release (not part of version control)
- Auto-generated documentation (incl. versioning)
- Deployment of documentation (keeping docs of older PCB revisions)

This repo uses a sample KiCAD PCB from the [Cicada Project](https://github.com/EnAccess/Cicada-GSM-HW).

As part of the Open BMS we have already explored some features of the amazing KiBot tool. Also, the recent release of KiCAD v8 enriches the native KiCAD CLI with some features

**Expected outcome:** The optimal outcome of this challenge would be a repository template including all above mentioned features and integrations. However we know time is short and anything getting us closer to this can be a great success (e.g. an early draft repo + a detailed specifications and to-do list).

## Getting Started

- Join the OSEAS24 Discord server: https://community.oseas.org/
- Introduce yourself in #introductions channel and join this topic’s channel
- Confirm you have access to the following Repos
  - https://github.com/EnAccess/oseas24-open-hardware-template-repo
- For physical participants: Bring a computer (and required Adapters) for some hacking 🤖🧑‍💻
- Read through the information and resources section

Contact person(s): Daniel (remote) / Martin (remote)

## Further information and resources

- https://github.com/LibreSolar/bms-c1/pull/48
- https://www.kicad.org/blog/2024/02/Version-8.0.0-Released/
- https://github.com/INTI-CMNB/KiBot
- KiCanvas: KiCad web viewer
  - Link: https://kicanvas.org/
  - Example: https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2FLibreSolar%2Fbms-c1%2Ftree%2Fmain%2Fkicad
- Interactive HTML BoM
  - https://github.com/openscopeproject/InteractiveHtmlBom
- Other example of nice project: https://github.com/OpenCleanEnergy/OpenMI
