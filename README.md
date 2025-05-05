<div align="center">

  <b>Doc Parser</b>
----------------------
a lightweight web app that parses legal documents and extracts key clauses to generate concise summaries

</div>

## Link

https://cool-centaur-624811.netlify.app/

## Why?

> tl;dr: it's a super useful pre-processing step before deeper compliance review.

- instant feedback: files are parsed in-browser, so summaries appear as soon as the file is uploaded to client, with no network round‑trip.
  
- zero usage fees: unlike GPT‑4 (at $0.01–$0.06 per 1 K tokens), this tool runs locally - no per‑document billing.
  
- pre-filter: by using this tool as an entry-point, you can extract core clauses client‑side, and drastically cut down the tokens sent to an LLM, consequently reducing spend.
  
**by embedding this lightweight parser as the first step into a larger workflow automation software, you gain speed, cost‑efficiency, and scalability, creating a best‑of‑both‑worlds pipeline: instant, rule‑based parsing up front, and ai‑driven analysis where it matters most.**

note that the limitation here is that it won’t scale for bulk document processing. if you need to process hundreds of docs in parallel or work with large-scale datasets, this solution wouldn’t fit that use case. it’s meant for individual cases or smaller-scale operations—like checking a couple of contracts or policies quickly.

## How?

- upload `sample.txt`
- click `View Report`
- report will be identical to `output.txt`
- instant, zero‑cost document processing + summarization
  






