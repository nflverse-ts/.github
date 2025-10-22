# NFLVerse TypeScript

Unofficial TypeScript ports of [nflverse](https://github.com/nflverse) packages for accessing NFL data.

## About

nflverse-ts provides TypeScript/JavaScript implementations of the nflverse data ecosystem. While these packages are community-maintained, **they are being developed with the approval and support of the nflverse team**.

Our mission is to bring the comprehensive NFL data access of nflverse to the TypeScript/JavaScript ecosystem, maintaining the same data integrity and ease of use that has made nflverse the standard for NFL analytics in R and Python.

## Core Principles

- **Data Fidelity**: Access the same authoritative nflverse data sources
- **Type Safety**: Full TypeScript support with comprehensive type definitions
- **Open Source**: All packages will always remain open source under permissive licenses
- **Community-Driven**: Built by the community, for the community
- **Cross-Platform**: Works in Node.js, Deno, Bun, and modern browsers

## Development Status

We are in the early stages of porting nflverse packages to TypeScript. Check back soon for updates, or watch this organization to be notified when packages are released.

## Relationship with nflverse

These TypeScript ports are **unofficial** implementations created and maintained by community contributors. However:

- Development has been approved by the nflverse team
- We follow nflverse data structures and conventions
- We contribute to and benefit from the broader nflverse ecosystem
- All data is sourced from official [nflverse-data](https://github.com/nflverse/nflverse-data) repositories

**Official nflverse packages:**
- **R**: [nflreadr](https://github.com/nflverse/nflreadr), [nflfastR](https://github.com/nflverse/nflfastR), [nflseedR](https://github.com/nflverse/nflseedr), [nflplotR](https://github.com/nflverse/nflplotR), [nfl4th](https://github.com/nflverse/nfl4th)
- **Python**: [nflreadpy](https://github.com/nflverse/nflreadpy)
- **Julia**: [NFLData.jl](https://github.com/john-b-edwards/nfldata.jl)

## Data Sources

All packages will access data from [nflverse-data](https://github.com/nflverse/nflverse-data), which provides:

- Play-by-play data (1999-present)
- Player statistics and rosters
- Team information and schedules
- Advanced metrics (EPA, WPA, etc.)
- Draft picks, injuries, depth charts
- And much more

Data is maintained by the nflverse team and updated automatically via GitHub Actions.

## Contributing

We welcome contributions from the community! Whether you're fixing bugs, adding features, improving documentation, or porting additional packages, your help is appreciated.

### How to Contribute

1. Check existing issues or open a new one to discuss your idea
2. Fork the relevant repository
3. Create a feature branch
4. Make your changes with tests and documentation
5. Submit a pull request

Please read the contributing guidelines in each repository for specific details.

### Port a Package

Interested in porting an nflverse package to TypeScript? We'd love your help! Open an issue to coordinate efforts and ensure we're not duplicating work.

## Community

- **Discord**: Join the [nflverse Discord](https://discord.com/invite/5Er2FBnnQa) - `#typescript` channel
- **Discussions**: Use GitHub Discussions in individual repos for questions and ideas
- **Issues**: Report bugs or request features through GitHub Issues

## License

All nflverse-ts packages are released under the MIT License, ensuring they remain free and open source forever.

Data from nflverse-data is licensed under CC-BY 4.0. Please attribute the nflverse project when using this data.

## Acknowledgments

Special thanks to:
- The [nflverse team](https://github.com/nflverse) for creating and maintaining the incredible data infrastructure
- [@tanho63](https://github.com/tanho63) for developing nflreadpy and supporting this TypeScript initiative
- [@mrcaseb](https://github.com/mrcaseb), [@guga31bb](https://github.com/guga31bb), and all nflverse contributors
- The broader NFL analytics community

## Stay Updated

- ⭐ Star this organization to follow our progress
- 👁️ Watch for announcements
- 🐦 Follow updates on Twitter: [#nflverse](https://twitter.com/search?q=%23nflverse)

---

**Note**: These packages are not affiliated with or endorsed by the National Football League. All data is publicly available and used in accordance with nflverse data licensing.
