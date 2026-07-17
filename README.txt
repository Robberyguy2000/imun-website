IMUN '26 static site
====================

26 pages (7 nav + 17 committee + guides + schedule) sharing one style.css.
Plain static HTML/CSS - no build step or JS. The sidebar, footer and page
chrome are identical on every page; edit them in every file (multi-file
search-and-replace) to keep them in sync.

Placeholder assets (overwrite with the real files, SAME names/paths):
  public/imunlogo.jpeg                    conference logo (kept on re-run)
  public/Images/genericheader.jpg         interior page-header background
  public/Images/Team/*.jpg                secretariat photos
  public/Images/Committees/commitee{N}logo.png  committee logos
  public/Images/Sponsors/sponsor{1-6}.png (1 gold, 2-3 silver, 4-6 bronze)
  public/Topics/commitee{N}topic{1|2}.pdf topic briefs
  public/Guides/*.pdf                     delegate guides ('25 prototype names kept)
  public/Downloads/*.pdf                  schedule, rules of procedure

Placeholder text: search the HTML for "TODO" (contact email, Instagram
handle, registration form link, fees, deadline, venue address).
