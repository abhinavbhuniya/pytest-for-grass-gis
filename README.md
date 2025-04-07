# pytest-for-grass-gis
# GSoC 2025 Proposal: Add pytest support for GRASS GIS Python testing framework

## 📌 Project Description
This project aims to modernize the testing framework of GRASS GIS by integrating support for `pytest`. GRASS currently uses a custom `unittest`-based module (`grass.gunittest`) that is verbose and outdated. Migrating to `pytest` will make writing tests easier, more readable, and more in line with modern Python practices.

## 📅 Timeline Summary
### Community Bonding (April–May)
- Understand `grass.gunittest` and `pytest`
- Set up development environment
- Get familiar with GRASS GIS build and test structure

### Phase 1 (May–June)
- Modularize comparison utilities
- Create initial pytest-compatible test cases
- Implement a fixture for GRASS sessions

### Midterm Deliverables
- pytest working test suite for select modules
- Basic fixture and utility support

### Phase 2 (July)
- Migrate more tests and utilities
- Patch `grass.script.setup` and `create_location`
- Add documentation and examples

### Final Weeks (August)
- Final refinements and test coverage report
- Submit for final evaluation

## 🎯 Plan to Contribute
- Contribute before coding period by:
  - Fixing failing tests
  - Writing basic pytest cases for smaller modules
  - Participating in discussions on GRASS Matrix chat
- Reach out to mentors regularly
- Stay active on GitHub and Matrix

## 📌 Links
- 🔗 [GRASS GIS GitHub repo](https://github.com/OSGeo/grass)
- 💡 [GSoC 2025 Idea Page](https://trac.osgeo.org/grass/wiki/GSoC/2025#Addpytestsupport)

---

