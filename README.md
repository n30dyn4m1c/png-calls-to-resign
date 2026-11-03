# Told to Resign. Almost No One Does.

By Neo Malesa.

Do public calls to resign actually work in Papua New Guinea? A scrollytelling data story tracing 27 public calls, made between 2019 and 2026, for a PNG politician, public servant or state company head to resign, step down or step aside, and what happened after each one.

Live site: https://n30dyn4m1c.github.io/png-calls-to-resign/

## What it found

- 27 calls aimed at 15 people. One person actually resigned: Prime Minister Peter O'Neill, who said on 26 May 2019 he would step down and formally resigned on 29 May.
- Four people stepped aside for a while: three ministers and the UPNG chancellor. Tkatchenko and Maladina were back in their portfolios within eight months; Joseph kept his other ministries and was later made Health Minister.
- Four more people lost their posts when the PM or a board moved or sacked them. Everyone else stayed: 16 of the 27 calls changed nothing.

## Files

- `index.html`: the whole story in one page, with the data embedded
- `data/png-resignation-calls.csv` and `data/data.json`: the dataset, with links to the news report of each call and of its outcome
- `assets/`: two illustrations (AI-generated, credited on the page, with WebP copies) and `share-card-resign.png`, the 1200×630 social preview. `parliament-600.webp` and `empty-chair-700.webp` are smaller copies for phones

### Data fields

`date`, `caller`, `callerRole`, `callerType` (Prime Minister, Government MP, Opposition MP, Civil society), `target`, `targetRole`, `targetType` (Prime Minister, Minister, MP, Public servant, SOE or statutory head), `reason`, `reasonType` (Personal conduct, Politics or performance), `outcome` (resigned, aside, moved, stayed, pending), `outcomeText`, `src`/`srcName` (report of the call), `osrc`/`osrcName` (report of the outcome), `outcomeDate`, `daysToOutcome`.

## Method and caveats

- A call is a named public figure or organisation publicly asking a named office-holder to resign, step down, step aside, be sacked or have their appointment revoked.
- When several people make the same demand in one report, the most senior caller is counted once. Days to leaving count from the most recent call before the person left.
- Sources are PNG and regional news outlets, searched in November 2026. The record is a floor, not a complete count: many calls never reach online archives.
- A call to resign is not proof of wrongdoing. Allegations are described as they were reported at the time.

## Corrections

Missing a call, or spotted an error? Email nmalesa@upng.ac.pg, or [open an issue](https://github.com/n30dyn4m1c/png-calls-to-resign/issues/new) with a link to the news report.
