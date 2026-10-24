<h1 align="center">Say-On 사연</h1>

<p align="center">
  <b>Every choice has a story.</b><br>
  A card game for talking. One table, one question, the whole room.
</p>

<p align="center">
  <a href="https://say-on.vercel.app"><b>Play in your browser →</b></a><br>
  <sub>No install, no sign-up. Best with two or more phones in the same room.</sub>
</p>

<p align="center"><a href="assets/say-on-promo-20261024.mp4"><img src="assets/say-on-promo-20261024.gif" alt="Say-On film shot from above a wooden table: three cards are dealt, one turns over for everyone at once, question prints land on the pile, balance pairs ask you to pick a side, and it ends on a fanned hand of cards." width="100%"></a></p>

<p align="center"><sub>Animated product screenshots using the app's own table, card and print art from this repository. No live room was opened. Play it in your browser at say-on.vercel.app.</sub><br><a href="assets/say-on-promo-20261024.mp4">Watch the full film</a> · <a href="assets/say-on-promo-20261024-poster.png">Still frame</a> · <a href="assets/say-on-promo-20261024-manifest.json">Capture details</a></p>

**사연** is the story behind a choice—the kind you tell when someone asks *why*. **Say on** means *keep talking*.

Say-On gives the people around a table something to start with. Pick a question, hear an unexpected answer and follow the conversation wherever it goes. There is no feed, score or winner.

## Bring everyone to the same table

<p align="center">
  <a href="https://say-on.vercel.app"><img src="assets/sayon-figma-02-final-20261023.png" width="430" alt="Say-On room screen, presented in a campaign card: enter an invite code or choose a room to join."></a>
</p>

One person opens a room and shares its invite code. Everyone else joins from their own phone, or chooses a room from the list. The host can add a 4 to 12 digit password; a quiet room clears itself away after 15 minutes.

## Pick a card. Give it a moment.

<p align="center">
  <img src="assets/balance-round.gif" width="300" alt="A Balance round: three cards are dealt, one is chosen, everyone votes between two options, and the hidden votes are revealed together.">
</p>

Three cards arrive on the table. The person whose turn it is picks one, and it opens for everyone at the same moment. What happens next depends on the deck.

<p align="center">
  <a href="https://say-on.vercel.app"><img src="assets/turn-over.gif" width="880" alt="Three illustrated cards sit face down on a wooden table. One is chosen and turns into a film print asking about the most recent thing someone tried for the first time. The current speaker and timer sit beside it."></a>
</p>

### Tell a story · 아이스브레이크

<p align="center">
  <a href="assets/step-3-talk.webp"><img src="assets/sayon-figma-01-final-20261023.png" width="430" alt="The Icebreaker screen: a question appears on a dated film print with its own photograph. Select the image to see the original product capture."></a>
</p>

17 open questions, each with a photograph and the date it was opened. The current speaker has a few minutes to answer before the host moves on. A small question—*What was the last thing you tried for the first time?*—can lead somewhere no one expected.

### Choose a side · 밸런스 게임

<p align="center">
  <a href="assets/game-balance-choose.webp"><img src="assets/sayon-figma-03-final-20261023.png" width="430" alt="The Balance deck: three illustrated card backs show pairs of everyday choices. Select the image to see the original product capture."></a>
</p>

60 everyday dilemmas, illustrated with 120 objects. Everyone chooses privately; the votes stay hidden until the last person answers. Both cards then turn over and the count appears. The result starts the conversation: *Why that one?*

## Keep the conversation close

<p align="center">
  <img src="assets/chat-open.webp" width="260" alt="The optional chat opens over the question. Messages appear as paper slips, with coloured names and a message field labelled 보내기.">
</p>

Tap **대화** to open the chat without leaving the question. Messages appear like slips of paper passed across the table, and an unread count lets you know when someone has added something.

## The thought behind the table

The wooden surface, film prints and illustrated choices give each round something tangible to gather around. Synchronized turns keep the group on the same question; hidden votes let each person make their own choice before seeing the room's answer.

I designed Say-On in Figma and built it with React and Supabase Realtime. This showcase follows the interaction from joining a room to revealing a choice, so you can see how the visual decisions and the multiplayer behaviour work together.

<p align="center">
  <a href="https://say-on.vercel.app"><b>Start a conversation →</b></a>
</p>

<details>
<summary>About the screens and source</summary>

The campaign cards were curated in Figma around original product captures. Select either deck card to inspect its unframed screenshot; the room card opens the live game. The GIFs show the product's card interactions. The source code is private.

</details>

<p align="center"><sub>Designed and built by <a href="https://github.com/EricEremos">EricEremos</a>.</sub></p>
