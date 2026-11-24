# Building a practical agent team

## The problem

Research, content production and client follow-up often span several roles. Veracto organized its internal agents around the people assigning the work, the agents responsible for each task and the sources the team needs to review the result.

## How work moves through the team

Chief of Staff coordinates work that crosses OpenBot roles. Content Lead can ask a researcher to gather sources, then work with production on a draft and return it for a human to review. Team members can go directly to the agent responsible for a known task. Each agent works with the company tools and resources assigned to its role.

## From meeting to client brief

Gbrain runs the meeting workflow in a dedicated background queue. A worker processes approved transcripts or approved excerpts and uses the original text to check the summary and its citations. It brings repeat submissions into the same meeting record and keeps a link back to the source. When the meeting is tied to a confirmed client record, it writes the meeting reference to that record in Notion CRM.

OpenBot agents use Gbrain to look up previous meetings and client context. They read the live Notion record for current CRM fields. We verified both routes against the same client record after the 21 November 2026 cutover. Chief of Staff later prepared a client brief with citations to the original meeting and the current CRM record.

## Original OpenBot setup · 4 November 2026

The original access check covered six company roles, permitted company-resource operations and selected out-of-scope requests. At that stage, we tested a handoff from Chief of Staff to the separate CRM Manager role and checked the returned result. Gbrain now handles the meeting and CRM workflow described above.

[View the team diagram from the original setup](team-map-hierarchy.png). The archived diagram uses avatars from [Bloub](https://github.com/NorbertBodziony/bloub) ([MIT license](BLOUB-LICENSE.txt)).

## Attribution

Veracto configured and integrated [OpenBot](https://github.com/nightly-labs/openbot) and [Gbrain](https://github.com/garrytan/gbrain) for its internal work. The consulting practice is described at [veracto.ai](https://veracto.ai/).
