# WASP Latex Poster -- BETTERPOSTER MOD
This Latex poster uses the baposter class, originally from http://www.brian-amberg.de/uni/poster. Versions are found in several places. The files on which this version is based are from circulation within WASP and exact origins are not known. 
The original WASP poster template can be found at https://github.com/pskarin/wasp-poster.

This is a modified version which incorporates some ideas from the BetterPoster, see https://www.youtube.com/watch?v=1RwJbhkCA58. It also fixes the horrible lower banner of the WASP template. Use at your own peril.

## Usage

To update the poster, modify the contents in the parts/ folder. The file header.tex contains convenience commands such as \title, \companylogo etc. Other files contain pure formatting. The logo images are in the folder template-images/. Place poster specific graphics in content-images/. Use \vspace{} to fill in where necessary and the tcolorbox package to create fancy boxes.

## Dependencies
As for the beamer template maintained by creichen (https://github.com/wasp-sweden/beamer-template) the template depends on the MinionPro and MyriadPro fonts. One guide to installing these fonts is found here: https://github.com/sebschub/FontPro. You can also remove the use of MinionPro and MyriadPro (look under FONTS AND COLORS in wasp-poster.tex) and fall back to regular fonts but this will not adhere to the WASP style guide.

## Colors

The following standard WASP colors are defined:
  - waspgrey
  - waspblue
  - wasppink

And the following colors are also defined for the poster template:
  - wasp_text
  - wasp_banner_light
  - wasp_banner_dark
