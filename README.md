# Football Management System - Frontend

Static HTML/CSS pages for a football management app (teams and players).
Built as part of my path to becoming a .NET Backend Developer. These pages will later become Razor Views in the ASP.NET Core version of the project.

## Pages

| Page | File | Description |
|---|---|---|
| Teams list | `HTML_files/teams.html` | Table of teams with name, country, type badge and a link to each team |
| Team details | `HTML_files/team-details.html` | Team info (country, type, coach) and a players table |
| Add team | `HTML_files/add-team.html` | Form with text inputs, continent list and club/national radio buttons |

## What I practiced

- **HTML:** semantic tags (`header`, `nav`, `main`), tables (`thead`/`tbody`), forms (`label`/`id`, `name`, `fieldset`), description lists
- **CSS:** box model, Flexbox, colors and typography, attribute selectors, reusable classes (`.badge`, `.field`, `.actions`)

## Project structure

```
project/
├── HTML_files/
│   ├── teams.html
│   ├── team-details.html
│   └── add-team.html
├── style.css
└── README.md
```

## Run it
- project link: [football-management-frontend](https://omar-ahmed62.github.io/football-management-frontend/HTML_files/teams.html)


##  Next Steps & Roadmap

### 1. Project Evolution (Short-Term)
- [x] **Mobile Responsiveness:** Implement CSS Media Query to ensure the entire layout adapts flawlessly to mobile screens.
- [x] **Theming via CSS Variables:** Refactor color properties using CSS Variables (`--primary-color`, `--bg-color`, etc.) to implement a **Dark Mode** toggle.

### 2. Learning & Skill Upgrading (Long-Term)
- [ ] Bootstrap components for the layout
- [ ] JavaScript basics: filter and sort the teams table
- [ ] Fetch teams from a JSON endpoint
- [ ] Connect the pages to the ASP.NET Core + EF Core backend


## Related

Backend (C# console app with ADO.NET and EF Core versions) => [Football-Management-System-ConsoleApp](https://github.com/omar-ahmed62/Football-Management-System-ConsoleApp)


