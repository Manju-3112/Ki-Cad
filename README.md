KiCad README
For specific documentation about building KiCad, policies and guidelines, and source code documentation see the Developer Documentation website.

You may also take a look into the Wiki, the contribution guide.

For general information about KiCad and information about contributing to the documentation and libraries, see our Website and our Forum.

Build state
KiCad uses a host of CI resources.

GitLab CI pipeline status can be viewed for Linux and Windows builds of the latest commits.

Release status
latest released version(s) Release status

🔗Files
•AUTHORS.txt - The authors, contributors, document writers and translators list
•CMakeLists.txt - Main CMAKE build tool script
•copyright.h - A very short copy of the GNU General Public License to be included in new source files
•Doxyfile - Doxygen config file for KiCad
•INSTALL.txt - The release (binary) installation instructions
•uncrustify.cfg - Uncrustify config file for uncrustify sources formatting tool
•_clang-format - clang config file for clang-format sources formatting tool

🔗Subdirectories

•3d-viewer - Sourcecode of the 3D viewer
•bitmap2component - Sourcecode of the bitmap to PCB artwork converter
•cmake - Modules for the CMAKE build tool
•common - Sourcecode of the common library
•cvpcb - Sourcecode of the CvPCB tool
•demos - Some demo examples
•doxygen - Configuration for generating pretty doxygen manual of the codebase
•eeschema - Sourcecode of the schematic editor
•gerbview - Sourcecode of the gerber viewer
•include - Interfaces to the common library
•kicad - Sourcecode of the project manager
•libs - Sourcecode of KiCad utilities (geometry and others)
•pagelayout_editor - Sourcecode of the pagelayout editor
•patches - Collection of patches for external dependencies
•pcbnew - Sourcecode of the printed circuit board editor
•plugins - Sourcecode for the 3D viewer plugins
•qa - Unit testing framework for KiCad
•resources - Packaging resources such as bitmaps and operating system specific files
•bitmaps_png - Menu and program icons
•project_template - Project template
•scripting - Python integration for KiCad
•thirdparty - Sourcecode of external libraries used in KiCad but not written by the KiCad team
•tools - Helpers for developing, testing and building
•translation - Translation data files (managed through Weblate for most languages)
•utils - Small utils for KiCad, e.g. IDF, STEP, and OGL tools and converters
