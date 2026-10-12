<p align="center">
  <img src="assets/banners/bulletin_board_system_portal.png" alt="Bulletin Board System Portal" width="100%">
</p>

<h1 align="center">Bulletin Board System Portal</h1>

<p align="center">
  A directory, showcase, and resource hub for Bulletin Board Systems.
</p>

<p align="center">
  <strong>Directory</strong> · <strong>Showcase</strong> · <strong>Software</strong> · <strong>Networks</strong> · <strong>Media</strong> · <strong>Resources</strong>
</p>

## About the Project

The **Bulletin Board System Portal** is a community-oriented project for discovering, documenting, and showcasing Bulletin Board Systems and the culture around them.

The goal is to build more than a simple connection list. Each BBS can eventually have a richer profile with public connection information, software, supported protocols, networks, screenshots, videos, and other details that help visitors understand what makes the system unique.

The project is intended to cover both active systems and historically significant BBSs while also providing an organized place to discover BBS software, FTN communities, terminal clients, video channels, tutorials, and related projects.

## Portal Areas

### BBS Directory

A browsable directory of Bulletin Board Systems, with room to organize systems by:

- Active or historical status
- BBS software
- Supported protocols
- FTN or other network membership
- Region or country when publicly provided
- Features and areas of interest

Directory entries should contain only connection and SysOp information intended for public distribution.

### BBS Showcase

A visual area for showing what BBSs actually look like rather than reducing them to a hostname and port number.

Planned showcase material includes:

- Login and welcome screens
- Main menus
- Message and file areas
- ANSI, ASCII, and other terminal artwork
- Themes and interface designs
- Door and game menus
- Screens from both current and historical systems

### BBS Software

A high-level guide to Bulletin Board System software and related projects. The intent is not to duplicate each project's own documentation, but to help visitors identify software, see examples of systems using it, and find the appropriate project resources.

### Networks

A discovery area for FTNs and other BBS-oriented networks, including information useful for understanding where systems participate and how the broader BBS community is connected.

### Media

A curated collection of BBS-related media, including:

- YouTube channels
- BBS tours and walkthroughs
- Setup and administration videos
- Interviews
- Documentaries
- Retro-computing channels with meaningful BBS coverage

### Resources

Useful projects and tools for people visiting, operating, or learning about BBSs, such as terminal clients, BBS software, community projects, archives, and other relevant resources.

## Planned BBS Profile

Individual BBS entries are expected to grow toward a consistent format similar to:

```text
BBS Name
Status
SysOp
BBS Software
Platform
Location / Region (optional)

Connection Information
  Telnet
  SSH
  RLogin
  Web / Website

Networks
Features
Description
Screenshots
Videos
Related Links
```

Not every system will use every field. Historical systems may focus more heavily on archived information and preserved screenshots, while active systems can include current public connection details.

## Planned Repository Layout

```text
bulletin-board-system-portal/
├── assets/
│   └── banners/
├── bbs/
│   └── <bbs-name>/
│       ├── README.md
│       └── screenshots/
├── directory/
│   ├── active.md
│   ├── historical.md
│   ├── by-software.md
│   └── by-network.md
├── software/
├── networks/
├── media/
├── resources/
├── CONTRIBUTING.md
└── README.md
```

This structure is intentionally a starting point and can evolve as the portal begins receiving real systems and community contributions.

## Submission Principles

When BBS submissions are opened, the project will follow a few basic rules:

- Submit only connection details intended to be public.
- Do not submit passwords, private credentials, or private user information.
- Screenshots should be owned by the contributor or submitted with permission.
- Active, inactive, and historical systems should be clearly identified.
- Information should be descriptive rather than promotional whenever possible.
- Corrections from SysOps and project maintainers are encouraged.

## Project Status

The Bulletin Board System Portal is in its initial foundation stage. The repository structure, directory format, contribution process, and first system profiles are being developed.

The first goals are to establish:

1. A consistent BBS directory entry format
2. A screenshot and showcase format
3. Software and network indexes
4. A curated media section
5. Contribution guidelines for SysOps and community members

## Future Direction

The repository is being designed so its structured content can later support a more visual browsing experience, including the possibility of a GitHub Pages site with searchable or filterable directory views.

The GitHub repository will remain the source of truth for the underlying directory and community-maintained content.

## Contributing

Contribution guidelines and submission templates will be added as the initial directory format is finalized.

SysOps, BBS software developers, network coordinators, video creators, and members of the BBS community will be welcome to contribute corrections, screenshots, public system information, and useful resources.

---

<p align="center">
  <strong>Bulletin Board System Portal</strong><br>
  Directory · Showcase · Resources<br><br>
  <em>Twinkle BBS</em>
</p>
