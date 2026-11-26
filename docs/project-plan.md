# Project Plan

Required deliverable, written in Chapter 11 and updated as things change.
Keep it to this one page.

In Chapter 11, copy your team's `[Team plan]` issue (in `practice-pr`) into
this file:

| `[Team plan]` issue | This file |
|---|---|
| Topic | 1. The tool - One sentence |
| Track | 1. The tool - Track |
| Input / Process / Output | 2. Scope |
| Libraries (whitelist only) | 3. Open source we plan to use |
| Roles | 4. Team and roles |

## 1. The tool

- **Name**: Student Attendance Checker
- **One sentence**: Reads a student attendance CSV file and prints a formatted table of students with low attendance for a course instructor.
- **Category**: data processing
- **Track**: A only

## 2. Scope - input, one processing step, output

| | Our project |
|---|---|
| **Input** | attendance.csv (student_id, name, attended, total, rate) |
| **Processing step** | filter rows where rate < 80 |
| **Output** | formatted terminal table and low_attendance.xlsx |

**Definition of done**: one run command, one input, one output result.
Anything beyond that is track B, not the baseline.

## 3. Open source we plan to use

| Library | Why we need it | On the whitelist? |
|---|---|---|
| pandas | reads the CSV file and filters rows by attendance percentage | yes |
| rich | formats and prints the filtered results as a clean terminal table | yes |
| openpyxl | saves the filtered summary to an Excel file | yes |

One row for each library. For example: `| pandas | reads servers.csv | yes |`

Libraries not covered in class have a recipe card - read it before you add one.

## 4. Team and roles

Write GitHub usernames (for example @gildong-hong). In a team of two or three,
one person can take two roles. Roles can rotate later. If roles change, update
this table.

| Role | GitHub username |
|---|---|
| PM | @yonzanbibek |
| Developer | @rajivtmg-source |
| Documentation | @vaxo56735-ai |
| Reviewer | @chaudharyarbin17-creator |

## 6. Risks

| What could go wrong | What we will do about it |
|---|---|
| \<e.g. our input file has empty cells or extra columns\> | \<e.g. shrink to one column and validate it\> |
