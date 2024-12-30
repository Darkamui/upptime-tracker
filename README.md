# Upptime Tracker

_Why use Upptime and not host your own uptime tracker ?_

If you want to have an uptime tracker for your sites hosted on a vps, you would theoretically need the tracker to be on a different server for it to be able to send a failure update. Instead of paying for an extra server to host an uptime tracker to track the wanted server, Upptime allows for uptime checks using:

Github Actions to deploy the uptime test following a schedule

Github Issues to notify if a website is unreachable

Github Pages to display your upptime dashboard

- Start a new template repo from upptime/upptime (include all branches, set to public for unlimited minutes)
- in developer settings, generate new fine grained token for created repo
- Set actions,contents,issues and workflows access to read&write
- Copy token to created repo secrets and variables in actions 'GH_PAT'
- edit .upptimerc.yml as needed for your needs (modify owner, repo, sites,baseurl, remove cname line)

This repository contains the open-source uptime monitor and status page for [Daniel Jerusalmy](https://Darkamui.github.io/upptime-tracker), powered by [Upptime](https://github.com/upptime/upptime).

[![Uptime CI](https://github.com/Darkamui/upptime-tracker/workflows/Uptime%20CI/badge.svg)](https://github.com/Darkamui/upptime-tracker/actions?query=workflow%3A%22Uptime+CI%22)
[![Response Time CI](https://github.com/Darkamui/upptime-tracker/workflows/Response%20Time%20CI/badge.svg)](https://github.com/Darkamui/upptime-tracker/actions?query=workflow%3A%22Response+Time+CI%22)
[![Graphs CI](https://github.com/Darkamui/upptime-tracker/workflows/Graphs%20CI/badge.svg)](https://github.com/Darkamui/upptime-tracker/actions?query=workflow%3A%22Graphs+CI%22)
[![Static Site CI](https://github.com/Darkamui/upptime-tracker/workflows/Static%20Site%20CI/badge.svg)](https://github.com/Darkamui/upptime-tracker/actions?query=workflow%3A%22Static+Site+CI%22)
[![Summary CI](https://github.com/Darkamui/upptime-tracker/workflows/Summary%20CI/badge.svg)](https://github.com/Darkamui/upptime-tracker/actions?query=workflow%3A%22Summary+CI%22)

With [Upptime](https://upptime.js.org), you can get your own unlimited and free uptime monitor and status page, powered entirely by a GitHub repository. We use [Issues](https://github.com/Darkamui/upptime-tracker/issues) as incident reports, [Actions](https://github.com/Darkamui/upptime-tracker/actions) as uptime monitors, and [Pages](https://Darkamui.github.io/upptime-tracker) for the status page.

<!--start: status pages-->
<!-- This summary is generated by Upptime (https://github.com/upptime/upptime) -->
<!-- Do not edit this manually, your changes will be overwritten -->
<!-- prettier-ignore -->
| URL | Status | History | Response Time | Uptime |
| --- | ------ | ------- | ------------- | ------ |
| <img alt="" src="https://icons.duckduckgo.com/ip3/www.j-web.ca.ico" height="13"> [J-web](https://www.j-web.ca) | 🟩 Up | [j-web.yml](https://github.com/Darkamui/upptime-tracker/commits/HEAD/history/j-web.yml) | <details><summary><img alt="Response time graph" src="./graphs/j-web/response-time-week.png" height="20"> 302ms</summary><br><a href="https://Darkamui.github.io/upptime-tracker/history/j-web"><img alt="Response time 342" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Fj-web%2Fresponse-time.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/j-web"><img alt="24-hour response time 275" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Fj-web%2Fresponse-time-day.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/j-web"><img alt="7-day response time 302" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Fj-web%2Fresponse-time-week.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/j-web"><img alt="30-day response time 347" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Fj-web%2Fresponse-time-month.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/j-web"><img alt="1-year response time 342" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Fj-web%2Fresponse-time-year.json"></a></details> | <details><summary><a href="https://Darkamui.github.io/upptime-tracker/history/j-web">100.00%</a></summary><a href="https://Darkamui.github.io/upptime-tracker/history/j-web"><img alt="All-time uptime 99.99%" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Fj-web%2Fuptime.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/j-web"><img alt="24-hour uptime 100.00%" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Fj-web%2Fuptime-day.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/j-web"><img alt="7-day uptime 100.00%" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Fj-web%2Fuptime-week.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/j-web"><img alt="30-day uptime 100.00%" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Fj-web%2Fuptime-month.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/j-web"><img alt="1-year uptime 99.99%" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Fj-web%2Fuptime-year.json"></a></details>
| <img alt="" src="https://icons.duckduckgo.com/ip3/fe4fs.j-web.ca.ico" height="13"> [FE4FS](https://fe4fs.j-web.ca) | 🟩 Up | [fe-4-fs.yml](https://github.com/Darkamui/upptime-tracker/commits/HEAD/history/fe-4-fs.yml) | <details><summary><img alt="Response time graph" src="./graphs/fe-4-fs/response-time-week.png" height="20"> 201ms</summary><br><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs"><img alt="Response time 231" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Ffe-4-fs%2Fresponse-time.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs"><img alt="24-hour response time 165" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Ffe-4-fs%2Fresponse-time-day.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs"><img alt="7-day response time 201" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Ffe-4-fs%2Fresponse-time-week.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs"><img alt="30-day response time 235" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Ffe-4-fs%2Fresponse-time-month.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs"><img alt="1-year response time 231" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Ffe-4-fs%2Fresponse-time-year.json"></a></details> | <details><summary><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs">100.00%</a></summary><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs"><img alt="All-time uptime 97.56%" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Ffe-4-fs%2Fuptime.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs"><img alt="24-hour uptime 100.00%" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Ffe-4-fs%2Fuptime-day.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs"><img alt="7-day uptime 100.00%" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Ffe-4-fs%2Fuptime-week.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs"><img alt="30-day uptime 100.00%" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Ffe-4-fs%2Fuptime-month.json"></a><br><a href="https://Darkamui.github.io/upptime-tracker/history/fe-4-fs"><img alt="1-year uptime 97.56%" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDarkamui%2Fupptime-tracker%2FHEAD%2Fapi%2Ffe-4-fs%2Fuptime-year.json"></a></details>

<!--end: status pages-->

[**Visit our status website →**](https://Darkamui.github.io/upptime-tracker)

## 📄 License

- Powered by: [Upptime](https://github.com/upptime/upptime)
- Code: [MIT](./LICENSE) © [Anand Chowdhary](https://anandchowdhary.com), supported by [Pabio](https://pabio.com)
- Data in the `./history` directory: [Open Database License](https://opendatacommons.org/licenses/odbl/1-0/)
