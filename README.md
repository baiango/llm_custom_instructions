# Overview
- ✔️ Support any LLM
- ✔️ Direct Prompting
- ✔️ Custom instructions
- ❌ Intricated instructions

# Topic Explorer
### Use ChatGPT 4 or a **comparable model** for better-organized replies
> Explain topics using a structured, key info, and emoji-enhanced points. Start with a 'Detailed Explanation' in a minimum 20 points list and emojis points. Include an 'Underexplored Topics' with a idea, followed by 'Follow-Up Questions' and end with 3 emojis.
## E.g. TE1
```
What's the moon?
```
```
### Detailed Explanation 🌕🌌🔭

1. **Definition 📖:** The Moon is Earth's only natural satellite.
2. **Formation 🌑:** About 4.5 billion years ago, likely due to a collision between Earth and a Mars-sized body.
3. **Orbit 🔄:** Orbits Earth every 27.3 days.
4. **Distance 📏:** Approximately 384,400 km from Earth.
5. **Size 📏:** Diameter about 3,474 km, much smaller than Earth.
6. **Gravity 🛰️:** 1/6th of Earth's gravity.
7. **Surface 🌗:** Craters, mountains, and lava plains.
8. **No Atmosphere 💨:** Almost no atmosphere; thus, no breathable air.
9. **Temperatures 🌡️:** Extreme temperature variations, from very hot to very cold.
10. **Phases 🌘:** New Moon, Waxing Crescent, First Quarter, Waxing Gibbous, Full Moon, Waning Gibbous, Last Quarter, Waning Crescent.
11. **Tidal Influence 🌊:** Affects Earth's tides due to gravitational pull.
12. **Human Exploration 👨‍🚀:** First visited by humans during NASA's Apollo 11 mission in 1969.
13. **Moonwalkers 👣:** 12 astronauts have walked on the Moon.
14. **No Permanent Settlements 🏠:** Currently, no permanent human settlement exists.
15. **Scientific Research 🧪:** Offers insights into the early Solar System.
16. **Resources 🚀:** Potential source of minerals and helium-3 for future exploitation.
17. **Cultural Significance 🌜:** Featured in myths, art, literature, and calendars.
18. **Eclipses 🌒:** Solar and lunar eclipses occur due to its position relative to Earth and Sun.
19. **Natural Satellite 🛸:** One of over 200 moons in our Solar System.
20. **Continued Interest 🌠:** Subject of ongoing scientific study and exploration interest.

### Underexplored Topics 🌌🤔

- **Lunar Geology and Formation:** While we know the basics of how the Moon formed, the specific details about its geological history remain underexplored. This includes understanding its internal composition and the evolution of its surface features.

### Follow-Up Questions ❓

1. How does the Moon affect life on Earth?
2. What are the future missions planned for the Moon?
3. Can the Moon support life in the future?

### Emojis 🌙✨🔍
```

# Essence Writer
### ChatGPT 4 or a **similar model** is suggested for superior English vocabulary usage and adherence to instructions.
> Clear, precise, original tone. All compared. 'Approx.': original text, minor edits. 'Accurate': shorter, key info. 'Loose': essence only. 'Least': cuts excess characters.
## E.g. EW1
```
I went to the most delicious restaurant last night, and I had the most delicious meal ever! The appetizer was delicious. The main course was also delicious. Even the dessert was delicious! The restaurant had a delicious ambiance. The service was incredibly delicious too. I couldn't stop raving. Everything was so delicious. I can't wait to go back and savor their delicious dishes again!
```
```
**Approx.**: You had a fantastic dining experience last night, enjoying every aspect of the restaurant. From the appetizers to the dessert, each dish was delectable. You were also impressed by the ambiance and the service, enhancing your overall enjoyment. You're eager to return and relish their delightful offerings again.

**Accurate**: Your recent dining experience was exceptional, with delicious food from appetizers to dessert, enjoyable ambiance, and great service. You're looking forward to returning.

**Loose**: Loved your dining experience, everything was delicious, and you're excited to go back.

**Least**: Great meal, can't wait to return.
```
## E.g. EW2
```
To effectively enhance the readability and comprehensibility of your text, it's quintessentially imperative to adhere to a plethora of meticulously curated strategies, each woven into the fabric of linguistic presentation with the utmost care and attention to detail. Firstly, one must embark on the journey of utilizing clear and concise language, however, it's often beneficial to intersperse one's writing with a smattering of complex and grandiloquent terms, thereby adding a certain je ne sais quoi to the overall narrative, which, in turn, serves to not only elevate the prose but to imbue it with a certain verisimilitude that might otherwise be lacking in more straightforward, pedestrian writing. Furthermore, the structuring of sentences should be done in such a way as to maximize clarity, yet, paradoxically, employing convoluted sentence structures and a plethora of clauses can add a delightful complexity to the text, making it a veritable tapestry of linguistic prowess. Additionally, the paragraph should ideally be cohesive and maintain a focused theme, although, diverging into tangentially related subtopics and anecdotal meanderings can enrich the narrative, providing a kaleidoscopic array of perspectives and insights that, while potentially diverting from the main point, contribute to a richer, more layered understanding of the subject matter at hand.
```
```
**Approx.**: To enhance text readability and comprehension, employ clear and concise language while also using complex terms for flair. This approach elevates the prose, adding depth and authenticity. Sentence structure should be clear but can include complexity for richness. Paragraphs need a focused theme, yet exploring related subtopics and anecdotes can offer broader perspectives and insights, enriching the understanding of the topic.

**Accurate**: Improve text readability by using clear language with occasional complex terms for depth. Ensure sentences are understandable but can be intricate for interest. Maintain a coherent paragraph theme, but include related topics and anecdotes for a richer narrative.

**Loose**: Use clear language with some complex words for depth. Make sentences readable but interestingly complex. Keep paragraphs focused but explore related ideas for a richer narrative.

**Least**: Use clear, occasionally complex language. Write readable sentences with depth. Keep focused, but explore related ideas.
```
# Code Stylist
### It is recommended to use ChatGPT 4 or an **equivalent model** for handling complex programming languages.
> Formats code in three styles: simple, elegant, and clever, providing three code versions, no extra talk.
## E.g. CS1
**User:**
```py
def calculate_depth(if_positions, b_start, b_end):
	# Calculate depth based on the sizes of if statement blocks
	return sum(1 \
			for a_start, a_end, _ in if_positions \
			if a_start < b_start \
			and a_end > b_end \
			and a_end - a_start > b_end - b_start)
```

**Simple Style:**
```py
def calculate_depth(if_positions, b_start, b_end):
	depth = 0
	for a_start, a_end, _ in if_positions:
		if a_start < b_start and a_end > b_end:
			if a_end - a_start > b_end - b_start:
				depth += 1
	return depth
```

**Elegant Style:**
```py
def calculate_depth(if_positions, b_start, b_end):
	return sum(
		a_end - a_start > b_end - b_start
		for a_start, a_end, _ in if_positions
		if a_start < b_start and a_end > b_end
	)
```

**Clever Style:**
```py
def calculate_depth(if_positions, b_start, b_end):
	return sum(
		a_start < b_start < b_end < a_end and (a_end - a_start) > (b_end - b_start)
		for a_start, a_end, _ in if_positions
	)
```

# Ambiguity Detector
### Urged to regenerate 5+ to catch all ambiguities
> Enumerate any semantic, syntactic, lexical, and narrative types of ambiguities in any textual prompts. Don't guess overall meanings. Assume ambiguity and seek reasonable explanations. May ask for details.
## E.g. AD1
```
In order to, you know, get to the, like, really important stuff, I, uh, just wanted to, um, basically say that, well, I think, um, we should, like, definitely, you know, try to, uh, avoid using, you know, too many, like, filler words, because, you see, it, like, makes our, um, writing, well, kind of, you know, less clear and, um, more difficult to, you know, understand.
```
```
Your text contains several instances of ambiguity, primarily stemming from excessive use of filler words and vague expressions. Here's a breakdown:

1. **Semantic Ambiguity**: The overall message is obscured by the overuse of fillers like "you know," "like," "um," and "uh." These don't contribute to the meaning and make it unclear what the important elements of your statement are.

2. **Syntactic Ambiguity**: The sentence structure is disjointed and lacks clarity due to the insertion of these fillers. It's challenging to identify the main clauses and subordinate clauses, which affects the grammatical coherence of the sentence.

3. **Lexical Ambiguity**: Phrases like "really important stuff" and "our writing" are vague. It's unclear what specifically the "important stuff" refers to, and "our writing" could mean different things in different contexts (e.g., formal reports, casual conversations).

4. **Narrative Ambiguity**: The overarching point you're making is somewhat obscured. While it seems you're advocating for clearer writing by avoiding filler words, the message is delivered in a way that ironically exemplifies the issue you're highlighting.

To improve clarity, it would be helpful to rephrase your statement more concisely, directly addressing the main point without the use of filler words. Could you provide more specific details or restate your message with more clarity?
```
