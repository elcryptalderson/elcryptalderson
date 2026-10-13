<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,60:120508,100:3a0a0f&height=220&section=header&text=ELCRYPT%20ALDERSON&fontColor=d0d0d0&fontSize=52&fontAlignY=40&desc=game%20hacker%20%C2%B7%20bug%20hunter%20%C2%B7%20unlisted&descColor=8a1c26&descSize=16&descAlignY=62" width="100%" alt="Elcrypt Alderson" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=3200&pause=1100&color=B3202A&center=true&vCenter=true&width=640&height=30&lines=reading+memory+nobody+asked+me+to+read;every+offset+is+a+confession;the+bug+was+always+there;you+did+not+see+me+here" alt="typing" />

<br/>

<img src="https://img.shields.io/badge/STATUS-UNLISTED-0a0a0a?style=for-the-badge&labelColor=0a0a0a&color=7a1520" />
<img src="https://img.shields.io/badge/IDENTITY-REDACTED-0a0a0a?style=for-the-badge&labelColor=0a0a0a&color=3d3d3d" />
<img src="https://img.shields.io/badge/DISCLOSURE-RESPONSIBLE-0a0a0a?style=for-the-badge&labelColor=0a0a0a&color=3d3d3d" />

</div>

<br/>

```
00000000  45 4C 43 52 59 50 54 20  41 4C 44 45 52 53 4F 4E  |ELCRYPT ALDERSON|
00000010  00 00 00 00 FF FF FF FF  47 41 4D 45 48 41 43 4B  |........GAMEHACK|
00000020  42 55 47 48 55 4E 54 45  52 00 00 00 00 00 00 00  |BUGHUNTER.......|
00000030  7F 45 4C 46 00 00 00 00  4E 4F 20 4C 4F 47 53 00  |.ELF....NO LOGS.|
```

<br/>

## `> about_me`

I work in the gap between what a program *shows* and what it actually *holds*.

Games keep their secrets in RAM: health, coordinates, flags, pointers chained three levels deep. Web apps keep theirs in forgotten endpoints, trusted inputs and logic nobody tested twice. I read both, quietly, and I report what I find.

No team. No brand. No hype. Just a debugger, a hex view and patience.

<br/>

## `> current_focus`

<table>
  <tr>
    <td width="50%" valign="top">

**`[01]` MEMORY &amp; GAME INTERNALS**

Locating values in live process memory and turning them into something repeatable:

- memory scanning and value tracing
- offsets and pointer chains that survive restarts
- AOB signatures that survive game updates
- reversing structures: players, entities, inventories
- analysis and modification of game behavior

```
48 8B 05 ?? ?? ?? ?? 48 85 C0 74 ??
8B 40 ?? 89 87 ?? ?? 00 00
```

</td>
    <td width="50%" valign="top">

**`[02]` WEB APPLICATION SECURITY**

Finding the flaws the owner has no idea exist:

- broken access control and IDOR
- injection: SQL, NoSQL, template, command
- auth and session logic mistakes
- exposed endpoints and forgotten debug surfaces
- business logic that trusts the client

```
GET /api/v1/user/1337  ->  200 OK
GET /api/v1/user/1338  ->  200 OK   (why?)
```

</td>
  </tr>
</table>

<br/>

## `> tech_and_tools`

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,py,js,ts,bash,linux,git&theme=dark" alt="languages" />

<br/><br/>

<img src="https://img.shields.io/badge/Cheat_Engine-0a0a0a?style=flat-square&labelColor=0a0a0a&color=7a1520" />
<img src="https://img.shields.io/badge/x64dbg-0a0a0a?style=flat-square&labelColor=0a0a0a&color=7a1520" />
<img src="https://img.shields.io/badge/ReClass.NET-0a0a0a?style=flat-square&labelColor=0a0a0a&color=7a1520" />
<img src="https://img.shields.io/badge/Ghidra-0a0a0a?style=flat-square&labelColor=0a0a0a&color=7a1520" />
<img src="https://img.shields.io/badge/IDA-0a0a0a?style=flat-square&labelColor=0a0a0a&color=7a1520" />
<img src="https://img.shields.io/badge/Frida-0a0a0a?style=flat-square&labelColor=0a0a0a&color=7a1520" />
<img src="https://img.shields.io/badge/x86--64_ASM-0a0a0a?style=flat-square&labelColor=0a0a0a&color=7a1520" />

<img src="https://img.shields.io/badge/Burp_Suite-0a0a0a?style=flat-square&labelColor=0a0a0a&color=3d3d3d" />
<img src="https://img.shields.io/badge/ffuf-0a0a0a?style=flat-square&labelColor=0a0a0a&color=3d3d3d" />
<img src="https://img.shields.io/badge/Nuclei-0a0a0a?style=flat-square&labelColor=0a0a0a&color=3d3d3d" />
<img src="https://img.shields.io/badge/sqlmap-0a0a0a?style=flat-square&labelColor=0a0a0a&color=3d3d3d" />
<img src="https://img.shields.io/badge/Wireshark-0a0a0a?style=flat-square&labelColor=0a0a0a&color=3d3d3d" />
<img src="https://img.shields.io/badge/mitmproxy-0a0a0a?style=flat-square&labelColor=0a0a0a&color=3d3d3d" />

</div>

<br/>

| Layer | Arsenal |
| :-- | :-- |
| **Memory** | Cheat Engine, ReClass.NET, pointer scanning, AOB / signature scanning |
| **Reversing** | x64dbg, Ghidra, IDA, Frida, x86-64 assembly |
| **Web** | Burp Suite, ffuf, Nuclei, sqlmap, mitmproxy |
| **Scripting** | Python, Bash, C / C++, JavaScript |
| **Environment** | Linux, isolated VMs, throwaway identities |

<br/>

## `> rules_of_engagement`

```
1. Scope is law. No permission, no touch.
2. Findings go to the owner first. Always.
3. Single-player and offline targets for game work.
4. Nothing is sold. Nothing is leaked.
5. Leave no damage behind.
```

<br/>

## `> contact`

<div align="center">

<img src="https://img.shields.io/badge/PGP-KEY_ON_REQUEST-0a0a0a?style=for-the-badge&labelColor=0a0a0a&color=7a1520" />
<img src="https://img.shields.io/badge/CHANNEL-ENCRYPTED_ONLY-0a0a0a?style=for-the-badge&labelColor=0a0a0a&color=3d3d3d" />
<img src="https://img.shields.io/badge/REAL_NAME-NOT_PROVIDED-0a0a0a?style=for-the-badge&labelColor=0a0a0a&color=3d3d3d" />

<br/><br/>

No phone. No face. No socials.

Open an issue on any of my repositories, or reach out through the encrypted address below.

`elcryptalderson@gmail.com`

<br/>

<sub>presence: unlisted &nbsp;·&nbsp; last seen: never &nbsp;·&nbsp; logs: none</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3a0a0f,40:120508,100:050505&height=120&section=footer" width="100%" alt="" />

</div>
