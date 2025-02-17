# Website Categories 

This folder is the home of the JSON file containing the info for the categories that are displayed on the website's home page. If any edits need to be made to these categories, just edit the data in the JSON and the home page will reflect your changes automatically.

A repository can have up to 20 tags. The list below also contains each category's blurb to ensure consistency in phrasing and length. Note that in some cases the category is plural but the corresponding tag is singular.

For each category this file contains it's title, [icon][icon dir] filepath, and category description. This data is read by the [category info javascript][js dir].

[icon dir]: ../assets/images/
[js dir]: ../js/category-info.js

- Applications: Browse scientific simulation codes and IT management tools - `application`
- Build Tools: Automate and simplify complex dependencies and deployments - `build-tools`
- Complete Catalog: Browse all LLNL open source projects - no tags required
- Data Management & Viz: Manage visualizations with robust features and configurable analysis - `data-management`, `data-viz`
- Math & Physics Libraries: Optimize solvers, higher order methods, and AMR frameworks - `math-physics`
- Performance & Workflow: Manage and scale complex workflows, tracking, and data collection - `performance`, `workflows`
- Portable Execution & Memory Mgmt: Automate data motion and memory allocation on advanced architectures - `memory-management`, `portability`
- Proxy Applications: Prepare for testing and porting applications - `proxy-application`
- System Software: Manage clusters and parallel environments - `system-software`

In general, topic tags raise a repo's visibility on GitHub and help users find related projects. The following tags, which are are not associated with the home page categories above, are recommended for LLNL repos: `amr` (adaptive mesh refinement), `checkpoint`, `cmake`, `cpp` (C++), `energy`, `exascale-computing`, `finite-elements`, `fortran`, `gpu`, `hpc`, `javascript`, `machine-learning`, `matlab`, `monte-carlo`, `mpi`, `neural-network`, `parallel`, `python`, `shell`, `simulation`, `solver`, `uncertainty-quantification`.
