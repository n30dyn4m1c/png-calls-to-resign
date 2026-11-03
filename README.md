# Told to quit. Almost no one does.

**Do public calls to resign actually work in Papua New Guinea?** A scrollytelling data story tracing 27 public calls, made between 2019 and 2026, for a PNG politician, public servant or state company head to resign, step down or step aside, and what happened after each one.

Live site: https://n30dyn4m1c.github.io/png-step-down/

## What it found

- 27 calls aimed at 15 people. One person actually resigned: Prime Minister Peter O'Neill, in May 2019.
- Three ministers stepped aside for a while. Two of them were later reinstated.
- Five more people lost their posts when the PM or a board moved them. The other 15 calls were ignored.
- Counting only real resignations, 8% of PNG calls worked. A German study of ministers from 1969 to 2005 found 13%.

## Files

- `index.html`: the whole story in one page, with the data embedded
- `data/png-resignation-calls.csv` and `data/data.json`: the dataset, with links to the news report of each call and of its outcome
- `assets/`: two illustrations (AI-generated, credited on the page)

### Data fields

`date`, `caller`, `callerRole`, `callerType` (Prime Minister, Government MP, Opposition MP, Civil society), `target`, `targetRole`, `targetType` (Prime Minister, Minister, MP, Public servant, SOE or statutory head), `reason`, `reasonType` (Personal conduct, Politics or performance), `outcome` (resigned, aside, moved, stayed, pending), `outcomeText`, `src`/`srcName` (report of the call), `osrc`/`osrcName` (report of the outcome), `outcomeDate`, `daysToOutcome`.

## Method and caveats

- A call is a named public figure or organisation publicly asking a named office-holder to resign, step down, step aside, be sacked or have their appointment revoked.
- Sources are PNG and regional news outlets, searched in November 2026. The record is a floor, not a complete count: many calls never reach online archives.
- A call to resign is not proof of wrongdoing. Allegations are described as they were reported at the time.

## Corrections

Missing a call, or spotted an error? [Open an issue](https://github.com/n30dyn4m1c/png-step-down/issues/new) with a link to the news report.
