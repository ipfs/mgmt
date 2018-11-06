# IPFS Team Planning, Management & Coordination threads

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](https://protocol.ai)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](https://ipfs.io/)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)

**tl:dr:** We have a **weekly, all-hands call** on Mondays. The time, date and other info for each week's call is announced in [an issue in this repository](https://github.com/ipfs/pm/issues). Propose agenda items for the call by commenting on the issue!

## Repo Index

- [How We Work](#how-we-work)
- [Teams](TEAM_STRUCTURES.md))
- [Asynchronous Communitication](#asynchronous-communication)
- [Synchronous Communication](#synchronous-communication)
  - [Weekly All Hands](#weekly-all-hands)
  - [Working Groups Weekly/BiWeekly Syncs](#working-groups-weeklybiweekly-syncs)
  - [Working Hours](#working-hours)
- [Tools](#tools)
  - [Zoom](#zoom)
  - [Calendar](#calendar)
  - [Coordination Toolkit](TEAM_COORDINATION_TOOLKIT.md)
  - [How to create a Roadmap](ROADMAP_HOW_TO.md)
  - [Resources for Distributed Teams](DISTRIBUTED_TEAMS.md)
- [Timezone: UTC](#timezone-utc)
- [Contribute](#contribute)
- [License](#license)

## How We Work

We use a loose agile approach. We deliberately designed a Org wide process that is very flexible, enabling each team to design an internal coordination strategy that suits their project needs, while keeping a baseline for team wide coordination around Roadmapping and [OKRs](OKR)

You can find a list of [`Distributed Teams` resources on tools, decision making, process and more](DISTRIBUTED_TEAMS.md), that we have been gathering, reviewing, discussing and experimenting.

## Asynchronous Communication

As an organization that operates at a planetary scale with multiple people from different timezones and schedules, we value tremendously the benefits of Asynchronous Communication. The art of writting things down for future selfs or future contributors is one of the key reasons that enables [so many contributors](https://github.com/ipfs/contributors-hex-grid#big-grid) to participate in the large endeavour of Distributing the Web with the IPFS Project.

Some golden recommendations:
- Prefer to open a issue vs sending a DM
- If you find documentation missing, treat it as a bug. Once you get your answer, contribute it so that it benefits others
- Use synchronous time wisely (only if needed), convert any output into an artifact that can be used by others (avoid Tribal Knowledge)

A few of our teams have a structured (documented) way on how they track work that you can consult and take inspiration from:
- [MGMT_JS_CORE_DEV](MGMT_JS_CORE_DEV.md)
- [MGMT_GOLANG_CORE_DEV](MGMT_GOLANG_CORE_DEV.md)

## Synchronous Communication

Synchronous Communication is phenomenal to transfer memes rapidly, clarify any outstanding questions, deep dive into hard topics together, get to know each other better and develop trust. The main pain point with Synchronous Communication is that if you were not present, you might miss out on important information that is relevant to you and your project. To overcome this limitation, **a core competency of the IPFS Org a a whole is to be stellar at taking notes and creating artifacts that represent any decision/announcement made during those synchronous conversations**. The corollary being: if it ain't written down and broadcasted, it didn't happen.

### Weekly IPFS All Hands

- **When:** Every Monday, 5pm UTC. See [calendar](https://calendar.google.com/calendar/embed?src=ipfs.io_eal36ugu5e75s207gfjcu0ae84@group.calendar.google.com).
- **How:** This takes place synchronously using [Zoom](#zoom).
- **Length:** 30 minutes.

This is a regular and reliable call where everyone who's working on any repository under the IPFS umbrella checks in and has a chance to either call attention to particular items, to make announcements, or to seek discussion of a topic. It's also a way for casual followers to get a high-level update on the pulse of the IPFS projects without having to follow all of the sprint calls. Newcomers are very welcome.

If you are interested in participating, please join us on [Zoom](#zoom).

You can find recordings of the [previous IPFS All Hands on a Youtube playlist on the IPFS channel](https://www.youtube.com/watch?v=hmAniA6g9D0&list=PLuhRWgmPaHtSGRSHdU9dbsukHKlihZZAe)

This calendar an other IPFS Community calls are tracked on the [IPFS Community Calendar](https://github.com/ipfs/community#calendar)

If you are hosting a call for the first time or interested in learning how to do it, consult the [HOST_A_CALL](HOST_A_CALL.md) guide.

### Working Groups Weekly/BiWeekly Syncs

- [`JS Core Dev`](https://github.com/ipfs/tm/issues/650)
- [`Go Core Dev`](https://github.com/ipfs/tm/issues/674)
- [`Dynamic Data & Capabilities`](https://github.com/ipfs/dynamic-data-and-capabilities/blob/master/README.md#bi-weekly-sync)
- [`Project WG`](https://github.com/ipfs/project#ipfs-project-working-group)
- [`IPLD BiWeekly`](https://github.com/ipfs/tm/issues/720)

### Working Hours

As the IPFS team is all over the world, we've picked a set of "working hours" during which we can overlap. The hours are:

```
16:00-19:00 Z/UTC daily or
18:00-21:00 CEST daily or
12:00-15:00 EST daily or
09:00-12:00 PDT daily
```

We aim to be available during these hours. Your mileage may vary.

## Tools

### Zoom

We use [Zoom](http://zoom.us/) for our community calls. This allows us to stream directly to YouTube (currently under maintenance), and to have calls with more than 25 users. Zoom may require a download before you are able to join. If you click on a Zoom link to a meeting room, it will automatically suggest the software to download. Please let us know if you have any issues with Zoom.

**Note:** Screen Sharing in Zoom under X11 requires compositor. Users of minimalist tilling window managers (i3, awesome, dwm)  will share a "black screen" by default. The fix is to use third-party compositor, eg. [Compton](https://github.com/chjj/compton).

### Calendar

YOu can consult all IPFS related calls and events on the [IPFS Community Calendar](https://calendar.google.com/calendar/embed?src=ipfs.io_eal36ugu5e75s207gfjcu0ae84@group.calendar.google.com&ctz=UTC) you can watch for events and sync to.

## Timezone: `UTC`

All of our times are set according to the **UTC** timezone (or should be). This is much easier than adjusting times manually to accommodate different time zones, for a distributed team. If our calendar's location is set to Reykjavík, Iceland, it is because Iceland is always on UTC time. It is recommended that you know your timezone's difference from UTC for ease of scheduling. Sites like http://everytimezone.com can help with this..

## Contribute

Feel free to join in. All welcome. Open an [issue](https://github.com/ipfs/pm/issues)!

This repository and all of our sprint calls fall under the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/contributing.md)

## License

[CC-BY-SA](LICENSE)
