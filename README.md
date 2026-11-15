# Witness Drills

Flash cards for Harper v. Saint Catherine's Children's Hospital. Every card comes from a witness's own prior statement, including what the witness says about the exhibits.

## How to drill

1. **Pick your deck.** Witnesses drill their own deck. Attorneys drill their own witness and the witness they will cross.
2. **Answer out loud before you flip.** Say the full answer as if you were on the stand. If you are somewhere quiet, write it down. Never flip first and decide you knew it.
3. **Grade yourself strictly.** Got it means the exact fact: every name, number, date, and place right. Close is Missed. "About 20" when the answer is "over 20" is Missed. Hesitating more than a few seconds is Missed.
4. **Finish every round.** The first round is the full deck. Each round after that is only the cards you missed. Keep going until a round has no misses. That is one clear.
5. **Clear your deck once a day.** Do it at the same time each day until the competition. Your progress saves, so you can stop mid-round and come back.
6. **Track your first round.** When you clear the full first round with no misses on two days in a row, move to speed rounds: answer each card in under three seconds.
7. **Drill with a partner twice a week.** The partner reads the front as an attorney would ask it. The witness answers in character, in a full sentence. The partner marks the card. Witnesses must also be able to answer when the partner asks it as a leading question.
8. **Start over when something changes.** If a card is edited or you take a few days off, press Start over to begin again with the full deck.

Keyboard: Space or Enter flips the card, 1 is Missed it, 2 is Got it.

## How it works

- Pick a witness. Round 1 is the full deck, in the order the cards appear in the statement.
- Flip each card (tap, Space, or Enter), then mark **Missed it** (1) or **Got it** (2).
- At the end of a round, the next round is only the cards you missed.
- When you get every card in a round right, the deck is cleared. Start it again for a fresh full round.
- Progress saves in your own browser, so you can close the page and pick up where you left off. **Start over** resets that witness.

## Editing cards

Each witness has a file in `decks/`. Each card is one line:

```js
{ id: "j61", front: "Question", back: "Answer (p. 26, ll. 88-90)" },
```

Give every new card a unique `id`. Removing a card is safe; saved progress skips it.

## Publishing on GitHub Pages

1. Create a repository and upload these files, keeping the `decks` folder.
2. Settings > Pages > Deploy from a branch > `main` / root.
3. Share the link GitHub shows (for example, `https://yourname.github.io/witness-drills/`).
