# 8 Code Review English Comments That Every Developer Needs

Eight lines for a code review: four for writing one and four for answering one. Each carries the reason it works and the weaker version most people reach for instead.

## The eight phrases

### 1. This one's optional, so ignore it if you disagree.
*/ðɪs wʌnz ˈɒpʃənəl səʊ ɪɡˈnɔːr ɪt ɪf juː ˌdɪsəˈɡriː/* — saying how much it matters
Instead of: Maybe change this?
Why it works: You already mark the small ones nit. This is the sentence version of that. Without it every comment sounds equally serious, and the author has to guess which ones you meant.
Example: This one's optional, so ignore it if you disagree. The build passes either way.
Tagalog: Opsyonal po ito, kaya huwag na ninyong pansinin kung hindi kayo sang-ayon.

### 2. What made you choose this approach?
*/wɒt meɪd juː tʃuːz ðɪs əˈprəʊtʃ/* — asking about the decision, not the person
Instead of: Why did you do it this way?
Why it works: The first version asks about the person. The second asks about the decision. Out loud they sound the same. In writing, only one of them sounds like blame.
Example: What made you choose this approach? I want to understand it before I ask for anything.
Tagalog: Ano po ang naging basehan ng paraang ito?

### 3. If this stays as it is, the next person will have to guess.
*/ɪf ðɪs steɪz æz ɪt ɪz ðə nekst ˈpɜːsən wɪl hæv tuː ɡes/* — naming the cost, not the fault
Instead of: This is a bit messy.
Why it works: Messy is your taste, and nobody argues with taste and wins. A cost is a fact the author can go and check. Once they've checked it, they've already agreed with you.
Example: If this stays as it is, the next person will have to guess. That's the only reason I'm raising it.
Tagalog: Kung mananatili po itong ganito, kailangan pang manghula ng susunod na magbabasa nito.

### 4. I might be missing something here.
*/aɪ maɪt biː ˈmɪsɪŋ ˈsʌmθɪŋ hɪə/* — leaving room to be wrong
Instead of: This is wrong.
Why it works: You're often right. Sometimes you're not. This line costs you nothing when you're right, and it saves the whole thread when you aren't.
Example: I might be missing something here, so tell me if this is deliberate.
Tagalog: Baka po may hindi ako nakikita rito.

### 5. You're right that this is confusing.
*/jɔː raɪt ðæt ðɪs ɪz kənˈfjuːzɪŋ/* — agreeing with what they saw
Instead of: It's fine once you know what it does.
Why it works: Every review comment has two parts. What they saw, and what they want done. The first is usually true. Agree with it, and the argument shrinks to the part you actually disagree about.
Example: You're right that this is confusing. Here's the reason I left it.
Tagalog: Tama po kayo, nakakalito nga ito.

### 6. Can you show me a case where this breaks?
*/kæn juː ʃəʊ miː ə keɪs weə ðɪs breɪks/* — asking for the evidence
Instead of: I don't think that's a real problem.
Why it works: This isn't a fight. You're asking for one example. If they have one, you've learned something. If they can't find one, you've both learned that too.
Example: Can you show me a case where this breaks? Then I'll fix it properly.
Tagalog: Maaari po ba ninyong ipakita kung saan ito nagfa-fail?

### 7. I disagree, but I'm happy to be convinced.
*/aɪ ˌdɪsəˈɡriː bʌt aɪm ˈhæpi tuː biː kənˈvɪnst/* — disagreeing without closing the door
Instead of: No, that wouldn't work.
Why it works: Disagree is a strong word, and it should be. The second half says the door is still open. Most written arguments start because one side sounded final.
Example: I disagree, but I'm happy to be convinced. Tell me what I'm not seeing.
Tagalog: Hindi po ako sang-ayon, pero kayang-kaya ninyo akong kumbinsihin.

### 8. This is faster to talk through than to type.
*/ðɪs ɪz ˈfɑːstə tuː tɔːk θruː ðæn tuː taɪp/* — moving it off the thread
Instead of: Let me explain again in more detail.
Why it works: A thread only grows. Every reply is one more thing the next reader has to get through. Ten minutes of talking ends what ten replies can't.
Example: This is faster to talk through than to type. Ten minutes at your desk?
Tagalog: Mas mabilis po itong pag-usapan kaysa i-type.

## The steps

Size · Question · Cost · Door

Four steps, and two of them exist only to put back the tone that writing takes out — the size at the front, the door at the end. Remember that order if you remember nothing else. A reviewer who sizes the comment, asks about the decision and names the cost gets the change made, and keeps the author on their side.

## Practise producing it

1. You've left five comments on one pull request and only one of them actually matters.
   Answer: This one's optional, so ignore it if you disagree.
   Why: You already mark the small ones nit. This is the sentence version of that. Without it every comment sounds equally serious, and the author has to guess which ones you meant.

2. You can't see why the author wrote it this way, and you want the reason.
   Answer: What made you choose this approach?
   Why: The first version asks about the person. The second asks about the decision. Out loud they sound the same. In writing, only one of them sounds like blame.

3. The change works, and you can already see the next person losing an hour to it.
   Answer: If this stays as it is, the next person will have to guess.
   Why: Messy is your taste, and nobody argues with taste and wins. A cost is a fact the author can go and check. Once they've checked it, they've already agreed with you.

4. You're about to say the logic is broken, and you've read it once.
   Answer: I might be missing something here.
   Why: You're often right. Sometimes you're not. This line costs you nothing when you're right, and it saves the whole thread when you aren't.

5. The reviewer says your function is hard to follow. They're right, and you still want to keep it.
   Answer: You're right that this is confusing.
   Why: Every review comment has two parts. What they saw, and what they want done. The first is usually true. Agree with it, and the argument shrinks to the part you actually disagree about.

6. A reviewer says this will break, and hasn't said where.
   Answer: Can you show me a case where this breaks?
   Why: This isn't a fight. You're asking for one example. If they have one, you've learned something. If they can't find one, you've both learned that too.

7. You've read their reason and you still think your version is better.
   Answer: I disagree, but I'm happy to be convinced.
   Why: Disagree is a strong word, and it should be. The second half says the door is still open. Most written arguments start because one side sounded final.

8. Four replies each, the thread is longer than the change, and nobody has moved.
   Answer: This is faster to talk through than to type.
   Why: A thread only grows. Every reply is one more thing the next reader has to get through. Ten minutes of talking ends what ten replies can't.

## Come back to this

**Day 3.** Three days ago you learned the four steps: size, question, cost, door.

New situation. You're reviewing someone far more senior than you, and you have found something real.

Which of the four steps do people drop first under that pressure, and which line would you make sure you still wrote?

**Day 7.** One week in. This is the one people get wrong.

The comment isn't about your change. It's about you, and it's sitting in a thread the whole team can read.

Two lines from this lesson still work here. Can you remember which, and how you'd keep the thread about the change?

---
On Duty English · https://ondutyenglish.com/practice/tech-the-code-review/
