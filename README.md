<h1 align="center">Say-On 사연</h1>

<p align="center"><b>A conversation card game for any group, played at one shared table.</b><br>
For friends, clubs, teams, classrooms and first meetings: open a room, draw a question, and talk.</p>

<p align="center">
  <a href="https://say-on.vercel.app"><img alt="지금 플레이하기 · say-on.vercel.app" src="assets/play-now.png" width="320"></a>
</p>

<p align="center">
  <a href="https://say-on.vercel.app"><img src="assets/hero.webp" width="880" alt="Say-On 사연 on a desktop: 하늘님의 차례 with a timer and a 다음 카드 button. On a round wooden table lies a film print with a photo of swimming goggles on a map and the question 가장 최근에 처음 해 본 일은 무엇이었나요?"></a>
</p>

<p align="center"><sub>Play in the browser, no install or sign-up: <a href="https://say-on.vercel.app"><b>say-on.vercel.app</b></a> · Best with two or more phones in the same room.</sub></p>

---

## The idea

**사연** is the story behind what someone chooses. **Say on** is an invitation to keep speaking.
Say-On puts one small, good question on the table and then gets out of the way. Everything that matters is an object on a shared wooden table: the question is a film print, a Balance choice is a card, and the chat is slips of paper passed across.

## How it works

<table>
  <tr>
    <td align="center" width="33%"><b>1 · 방 고르기</b><br><sub>Open a room, or pick one from the live list.</sub></td>
    <td align="center" width="33%"><b>2 · 게임 정하기</b><br><sub>The host chooses Icebreaker or Balance.</sub></td>
    <td align="center" width="33%"><b>3 · 이야기하기</b><br><sub>Everyone sees the same question at once.</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="assets/step-1-rooms.webp" width="240" alt="Phone lobby: 어떤 이야기부터 시작할까요?, an invite code field, and a paper list of rooms you can join, with 방 만들기 at the bottom."></td>
    <td align="center"><img src="assets/step-2-games.webp" width="240" alt="Phone waiting room for the host: 함께 시작할 준비를 해요, the two games, and the people in the room with who is ready."></td>
    <td align="center"><img src="assets/step-3-talk.webp" width="240" alt="Phone Icebreaker question: a film print on the table with a photo and the question 가장 최근에 처음 해 본 일은 무엇이었나요?"></td>
  </tr>
</table>

## Two games

<table>
  <tr>
    <td width="50%" valign="top"><b>아이스브레이크</b> · 17 open questions on film prints<br><sub>Three prints lie face down. The turn owner picks one, it turns over, and the question opens for the whole room with a talking timer.</sub></td>
    <td width="50%" valign="top"><b>밸런스 게임</b> · 60 everyday choices, 120 illustrations<br><sub>Each card back shows its two objects. Everyone picks a side, and the votes appear only when all have chosen.</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="assets/game-icebreaker.webp" width="320" alt="Three face-down film prints on a wooden table, numbered 01A, 02A and 03A."></td>
    <td align="center"><img src="assets/game-balance-choose.webp" width="320" alt="Three Balance card backs, each printed with its question's two objects."><br><img src="assets/game-balance.webp" width="320" alt="A Balance question, 계획 없는 하루가 생겼다면?, with two matching cards and their vote counts."></td>
  </tr>
</table>

## Chat that stays out of the way

<table>
  <tr>
    <td width="40%" align="center"><img src="assets/chat-open.webp" width="280" alt="The chat opened from the 대화 button: messages as paper slips, each name in its own colour, and a message field with 보내기."></td>
    <td width="60%" valign="middle">The chat is closed until you tap <b>대화</b>, with a small count for new messages. Open, the conversation reads like slips of paper passed across the table, and the message field is ready to type.</td>
  </tr>
</table>

## Rooms that feel private

<p align="center"><img src="assets/rooms-private.webp" width="880" alt="The locked-room dialog over the desktop lobby: a PIN field, 입장하기, and the notice 비밀번호가 맞지 않아요 · 남은 시도 4회."></p>

- **A live room list** on the first page: only rooms you can join, with search by name.
- **An optional 4 to 12 digit password** set by the host, checked on every way in, with a pause after five wrong tries.
- **Rooms clean themselves up** after 15 minutes without activity.

## Design notes

| Decision | Why |
| --- | --- |
| **The table is the stage** | One focal point per screen: the words sit on the paper margin, the object you act on lies on the table. |
| **Film prints for photos, a card deck for illustrations** | The Icebreaker photos are real photographs, so they are prints with a date imprint. The Balance art is illustration, so it is a clean card deck. |
| **One filled button per screen** | The next action is never in doubt; everything else is quiet text. |
| **Motion explains, never decorates** | Cards are dealt, lifted, turned over and slid away; with reduced motion they simply fade. |
| **Designed in Figma** | Screens and states are drawn at 390 and 1440 px, then built to match. |

## Built with

React 19 · TypeScript · Supabase (Postgres, Realtime, anonymous auth) · Vercel

151 automated tests · a four-browser real-time rehearsal on the live site (30 of 30 checks) · keyboard and reduced-motion support · phone and desktop layouts

<p align="center"><sub>Source code is private. © EricEremos. All rights reserved.</sub></p>
