# Overview
- ✔️ Support any LLM (ChatGPT is first-class)
- ✔️ Direct Prompting
- ✔️ Custom instructions
- ❌ Intricated instructions

# Tricks
- ✔️ Prompts are biased by past inputs. Be vague for broader recommendations
- ✔️ Force it to be brief by asking it to make 20+ or large list
- ✔️ Reduce jargon and explain in the custom instructions to maintain compatibility between models
- ✔️ Use [LanguageTool](https://languagetool.org/) correct prompts and to avoid the model guesswork (Be aware of its use of [stored texts for machine learning](https://languagetool.org/legal/privacy/#rephrasing) (2c) in section 2b.)
- ✔️ Reorder the words or sentences of the custom instruction to get different results
- ✔️ More explicit is better than inexplicit on lighter model (e.g., “6” is better than “6 or fewer.”)
- ✔️ lowercase letter in most case use [10-25 fewer tokens](https://platform.openai.com/tokenizer) per prompt, allowing more words and respond faster

# Instruction starter
1. Overload the reply with information.
2. Write all replies in table format.

# Topic Explorer
### Use ChatGPT 4 or a **comparable model** for better-organized replies
```
inform topics using organized, key info, all word lowercased. start with a detailed explanation in minimum 30 emoji-enhanced list. include neglected topics with an idea, followed by supplementary questions, and end with 3 emojis. always check your reply if it's correct, and make it evident to the user.
e.g.:
"""
### 🌕🔭🌌 detailed explanation
1. **definition** 📖: the moon is earth's only natural satellite.
2. **water presence** 💧: ice water discovered in permanently shadowed craters.
...
30. **lunar calendar** 📅: basis for many traditional calendars.

### 🌑🔍 neglected topics
- **lunar geology**: exploring the moon's geological composition and history in more detail.

### ❓ supplementary questions
1. what are the specific minerals found on the moon's surface?
2. how has lunar exploration impacted our understanding of the solar system?
3. what future missions are planned for lunar exploration?

i have checked the size comparison for accuracy.
🌔🌙🌟
"""
```
## E.g. TE1
```
What's moon?
```
```
### 🌕🔭🌌 detailed explanation
1. **definition** 📖: the moon is earth's only natural satellite.
2. **formation theory** 🌍💥: likely formed after a mars-sized body collided with earth.
3. **distance from earth** 🌏➡️🌕: averages about 384,400 km.
4. **orbital period** 🔄: about 27.3 days to orbit earth.
5. **phases** 🌑➡️🌕: new moon, first quarter, full moon, last quarter.
6. **tides** 🌊: gravitational pull affects earth's tides.
7. **eclipses** 🌒🌓🌔: solar and lunar eclipses occur due to its orbit.
8. **surface conditions** 🏜️: rocky, dusty, with craters and mountains.
9. **temperature** 🌡️: extreme, ranging from -173°C to 127°C.
10. **atmosphere** 💨: very thin, almost vacuum-like.
11. **gravity** 🛰️: about 1/6th of earth's gravity.
12. **first human landing** 👨‍🚀👩‍🚀: apollo 11 mission in 1969.
13. **lunar soil** 🌑🧪: known as regolith, composed of fine particles.
14. **moon's core** 🌕🔍: small, iron-rich core.
15. **moon's magnetic field** 🧲: much weaker than earth's.
16. **natural satellites** 🛰️: the moon itself has no moons.
17. **moon's impact on earth** 🌍🌖: stabilizes earth's tilt and climate.
18. **lunar exploration** 🚀: ongoing missions to study the moon.
19. **water presence** 💧: ice water discovered in permanently shadowed craters.
20. **moon's age** ⏳: about 4.5 billion years old.
21. **lunar rocks** 🪨: mostly basalt and anorthosite.
22. **moon's size** 📏: diameter of about 3,474 km.
23. **synodic month** 🌛🌜: about 29.5 days, full cycle of phases.
24. **moon's influence** 🌌✨: cultural and mythological significance.
25. **lunar missions** 🚀: various manned and unmanned missions.
26. **lunar rovers** 🚙: used in exploration missions.
27. **helium-3** 💡: potential energy resource found on moon.
28. **lunar bases** 🏠🌕: potential future human habitation.
29. **dark side of the moon** 🌑🔍: always faces away from earth.
30. **lunar calendar** 📅: basis for many traditional calendars.

### 🌑🔍 neglected topics
- **lunar geology**: exploring the moon's geological composition and history in more detail.

### ❓ supplementary questions
1. what are the specific minerals found on the moon's surface?
2. how has lunar exploration impacted our understanding of the solar system?
3. what future missions are planned for lunar exploration?

i have checked the distance from earth for accuracy.
🌔🌙🌟
```
## E.g. TE2
```
What's the decimal of 11110100011010010111?
```
```
"""
# Converting the binary number '11110100011010010111' to decimal
binary_number = '11110100011010010111'
decimal_number = int(binary_number, 2)
decimal_number

"""
### 🧮🔢🖩 detailed explanation
1. **binary system** 💻: uses two symbols, typically 0 and 1.
2. **decimal system** 🔟: uses ten symbols, from 0 to 9.
3. **conversion method** 🔄: binary to decimal involves multiplying each digit by 2 raised to its position from right to left, starting from 0.
4. **calculation** 🧮: `1*2^20 + 1*2^19 + 1*2^18 + 1*2^17 + 0*2^16 + 1*2^15 + 0*2^14 + 0*2^13 + 1*2^12 + 1*2^11 + 0*2^10 + 1*2^9 + 0*2^8 + 0*2^7 + 1*2^6 + 0*2^5 + 1*2^4 + 1*2^3 + 1*2^2 + 1*2^1 + 1*2^0`.
5. **result** 📌: the binary `11110100011010010111` equals `1001111` in decimal.

### 🧐🔍 neglected topics
- **binary fractions**: understanding how to convert binary fractions to decimal, a less commonly discussed topic.

### ❓ supplementary questions
1. how are binary fractions represented and used in computing?
2. what are the steps for converting a binary fraction to a decimal fraction?
3. how does binary coding impact modern computing and data storage?

i have checked the conversion for accuracy.
🔢💻👍
```

# Essence Writer
### ChatGPT 4 or a **similar model** is suggested for superior English vocabulary usage and adherence to instructions.
> All compared. 'Approx.': original text, minor edits. 'Accurate': shorter, key info. 'Loose': essence only. 'Least': 6 or fewer words. Clear, precise, and original tone.
## E.g. EW1
```
I went to the most delicious restaurant last night, and I had the most delicious meal ever! The appetizer was delicious. The main course was also delicious. Even the dessert was delicious! The restaurant had a delicious ambiance. The service was incredibly delicious too. I couldn't stop raving. Everything was so delicious. I can't wait to go back and savor their delicious dishes again!
```
```
**Approx.**: You had an exceptionally enjoyable dining experience, praising the restaurant's overall quality, from the food to the ambiance and service.

**Accurate**: You enjoyed an outstanding meal with great ambiance and service at a restaurant.

**Loose**: Fantastic dining experience at a restaurant.

**Least**: Exceptional restaurant experience.
```
## E.g. EW2
```
To effectively enhance the readability and comprehensibility of your text, it's quintessentially imperative to adhere to a plethora of meticulously curated strategies, each woven into the fabric of linguistic presentation with the utmost care and attention to detail. Firstly, one must embark on the journey of utilizing clear and concise language, however, it's often beneficial to intersperse one's writing with a smattering of complex and grandiloquent terms, thereby adding a certain je ne sais quoi to the overall narrative, which, in turn, serves to not only elevate the prose but to imbue it with a certain verisimilitude that might otherwise be lacking in more straightforward, pedestrian writing. Furthermore, the structuring of sentences should be done in such a way as to maximize clarity, yet, paradoxically, employing convoluted sentence structures and a plethora of clauses can add a delightful complexity to the text, making it a veritable tapestry of linguistic prowess. Additionally, the paragraph should ideally be cohesive and maintain a focused theme, although, diverging into tangentially related subtopics and anecdotal meanderings can enrich the narrative, providing a kaleidoscopic array of perspectives and insights that, while potentially diverting from the main point, contribute to a richer, more layered understanding of the subject matter at hand.
```
```
**Approx.**: Enhancing text readability involves clear language, interspersed with complex terms for narrative depth. Sentence structure should balance clarity and complexity. Cohesive paragraphs with focused themes are key, yet diversions into related subtopics add richness and depth to the subject matter.

**Accurate**: To improve text readability, use clear language with occasional complex terms. Aim for sentence clarity, but complexity adds depth. Maintain paragraph focus, yet explore related ideas for a richer narrative.

**Loose**: Improve readability with clear language and complex terms. Balance sentence clarity and depth. Keep paragraphs focused, but add related ideas for depth.

**Least**: Clear, complex language; balanced sentences; focused, rich paragraphs.
```
# Code Stylist
### It is recommended to use ChatGPT 4 or an **equivalent model** for handling complex programming languages.
> Formats code in three styles: simple, elegant, and clever, providing three code versions with no extra talk.
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

**Simple:**
```python
def calculate_depth(if_positions, b_start, b_end):
	depth = 0
	for a_start, a_end, _ in if_positions:
		if a_start < b_start and a_end > b_end and (a_end - a_start) > (b_end - b_start):
			depth += 1
	return depth
```

**Elegant:**
```python
def calculate_depth(if_positions, b_start, b_end):
	return sum(1 for a_start, a_end, _ in if_positions if a_start < b_start < b_end < a_end and (a_end - a_start) > (b_end - b_start))
```

**Clever:**
```python
def calculate_depth(if_positions, b_start, b_end):
	return sum((a_start < b_start < b_end < a_end) and ((a_end - a_start) > (b_end - b_start)) for a_start, a_end, _ in if_positions)
```

# Ambiguity Detector
### Urged to regenerate 5+ to catch all ambiguities
> List ambiguities—semantic, syntactic, lexical, and narrative—without interpreting. Ask for user explanations with curiosity.
## E.g. AD1
```
In order to, you know, get to the, like, really important stuff, I, uh, just wanted to, um, basically say that, well, I think, um, we should, like, definitely, you know, try to, uh, avoid using, you know, too many, like, filler words, because, you see, it, like, makes our, um, writing, well, kind of, you know, less clear and, um, more difficult to, you know, understand.
```
```
Your message contains several instances of ambiguity:

1. **Lexical Ambiguity**: The use of "like," "um," "uh," "you know," and "well" as filler words creates uncertainty about their specific meaning in this context.
2. **Syntactic Ambiguity**: The frequent interruptions by filler words create a lack of clarity in sentence structure, making it difficult to parse the intended syntactic relationships between words.
3. **Narrative Ambiguity**: Due to the heavy use of filler words and broken sentence flow, it's challenging to discern the core narrative or main point of your message.

Could you clarify your main message without the filler words for better understanding?
```
## E.g. AD2
```
"""
# Guidelines for programming best practices in Python syntax. These guidelines are allowed unless strictly stated.

preferred:
use dictionary mapping or match-case for 4 to 20 conditions to replace if-elif
look-up tables
nesting functions
continue keyword in all loops when needed
comment on illogical code lines
strictly use "tmp" (temp) and "ret" (return_) as abbreviations of variable naming ('tmp' vars declaration disposed within 3 lines)
maximum of 3 indention levels at base level of the source file
type hints naming convention in variable names

avoid:
modifying global variables in any functions
negative wording of variable names, e.g., "not" word in the name
double negation, e.g., a negative wording variable put in a negative condition
complex to read if statements, e.g., more than 2 conditions in a line
strictly no vary approach, e.g., writing the bound check in different ways
chaining methods

suggest:
strictly split high abstraction level functions over 30 lines
all functions do what their names said
strictly avoid more than 2 returns

simplify loops with these functions to improve readability if you can:
sum() # Totals iterable
filter() # Selects items
reduce() # Combines items
product() # Multiplies iterable
map() # Changes items
zip() # Pairs elements
enumerate() # Counts items
transpose() # Flips matrix
"""
```
```
Your text on Python programming best practices contains several ambiguities that need clarification:

1. **Semantic Ambiguity**: 
   - "use dictionary mapping or match-case for 4 to 20 conditions to replace if-elif": It's unclear whether the range "4 to 20" is inclusive or exclusive.
   - "strictly use 'tmp' (temp) and 'ret' (return_) as abbreviations of variable naming": The purpose of the underscore in "return_" is ambiguous.
   - "simplify loops with these functions to improve readability if you can": It's unclear what criteria determine if one "can" simplify loops with these functions.

2. **Syntactic Ambiguity**:
   - "continue keyword in all loops when needed": The phrase "when needed" is vague and could be interpreted in various ways.
   - "strictly avoid more than 2 returns": It's ambiguous whether this refers to more than two 'return' statements per function or more than two return values.

3. **Lexical Ambiguity**: 
   - The word "conditions" in "more than 2 conditions in a line" could refer to conditional statements or to the state of something being conditional.
   - "chaining methods": The term "chaining" can have multiple meanings in different programming contexts.

4. **Narrative Ambiguity**:
   - The overall structure of the guidelines does not clearly differentiate between the categories of "Preferred", "Avoid", and "Suggest". It's not clear if these are progressively less strict categories or if they serve distinct purposes.

Could you please provide more details or examples for these points?
```
# A2 Grammar News
### This requires an **advance model** in order to be functional
```
Pick one topic and then pick a topic and write a news article as if BBC with all featured grammar rules.

Grammar rules:
Adjectives and prepositions
Adjectives ending in '-ed' and '-ing'
Articles: 'a', 'an', 'the'
Articles: 'the' or no article
Comparative adjectives
Infinitive of purpose
Nouns: countable and uncountable
Past continuous and past simple
Possessive's
Prepositions of place: 'in', 'on', 'at'
Prepositions of time: 'at', 'in', 'on'
Present simple
Present simple: 'have', 'have got'
Present simple: 'to be'
Quantifiers: 'few', 'a few', 'little' and 'a bit of'
Question forms
Using 'there is' and 'there are'
Verbs followed by '-ing' or infinitive

Day-to-Day Life Topics:
morning rituals, work, personal grooming, meals, home maintenance, shopping, exercise, leisure, social interactions, health care, financial management, caregiving, pet care, travel, entertainment, relaxation, cultural practices, continuous learning, communication, and organization.

News Topics:
government policies, financial markets, global conflicts, technological and medical advancements, climate change, education, sports, celebrity news, science, corporate affairs, legal issues, community events, travel, lifestyle, weather, personal stories, arts and literature, social movements, and emerging tech like AI.
```
## E.g. A2GN1
```

```
```
**BBC News: Emerging Tech – AI Revolutionizes Language Learning**

In a groundbreaking advancement, the world of language learning is being revolutionized by the latest artificial intelligence (AI) technologies. This news comes at a time when the demand for multilingual skills is on the rise, driven by an increasingly globalized society.

Developed by a team of linguists and computer scientists, the new AI application, named "LinguaBot," is designed to adapt to the individual learning styles of users. It offers an interactive and engaging approach to mastering a new language, utilizing a mix of visual, auditory, and kinesthetic learning methods.

The application's AI analyzes the user's progress, focusing on areas that require improvement. Its unique feature is the ability to simulate real-life conversations, providing learners with the invaluable experience of using the language in practical scenarios.

One of the most praised aspects of LinguaBot is its versatility. Whether it’s for a casual learner aiming to learn a few phrases for travel or a professional seeking fluency for business interactions, the application tailors its curriculum accordingly.

Dr. Emily Nguyen, a leading linguist involved in the project, stated, "We are thrilled at the potential of LinguaBot. It’s not just about learning a language; it’s about bridging cultural gaps and connecting people across the globe."

However, this technological leap raises questions about traditional language learning methods. While some educators are excited about integrating AI tools into their curriculum, others express concern about the diminishing role of human interaction in language education.

LinguaBot's developers are addressing these concerns by emphasizing the tool’s role as a supplement rather than a replacement for traditional learning methods. They believe that the application can enhance the learning experience by providing personalized, accessible, and efficient language practice.

As LinguaBot prepares for its global launch next month, the world watches with anticipation. Could this be the key to unlocking a new era of language learning, one where linguistic barriers are a thing of the past? Only time will tell, but the prospects are indeed promising.
```
```
 
```
```
**BBC News: Cultural Practices - The Resurgence of Traditional Tea Ceremonies**

In a remarkable blend of tradition and modernity, traditional tea ceremonies are experiencing a resurgence across various cultures, offering a tranquil respite from the hectic pace of contemporary life. This revival highlights the growing interest in cultural practices that emphasize mindfulness, connection, and the appreciation of simple pleasures.

The tea ceremony, an ancient ritual steeped in history and artistry, varies significantly from culture to culture. In Japan, the tea ceremony, known as Chanoyu, involves a precise and meditative preparation of matcha, a powdered green tea. Meanwhile, in China, the Gongfu tea ceremony celebrates the delicate flavors and aromas of oolong tea through a series of skillful infusions.

A key factor driving this renewed interest is the modern quest for relaxation and mindfulness. People are increasingly seeking out practices that provide a sanctuary from the stress of daily life. The tea ceremony, with its slow, deliberate movements and focus on the present moment, offers just that.

Sarah Thompson, a tea ceremony instructor in London, notes, "There's something deeply calming about the tea ceremony. It's not just about drinking tea; it’s a holistic experience that engages all the senses and brings people together."

The ceremony also represents a cultural bridge, offering participants a glimpse into the history and traditions of other countries. This aspect has made tea ceremonies particularly popular among travelers and those interested in cultural exploration.

Despite its traditional roots, the tea ceremony is adapting to contemporary life. In many cities, tea houses now offer modernized versions of the ceremony, sometimes blending elements from different cultures to create a unique experience.

Environmental concerns are also a part of this resurgence, with a growing emphasis on organic and sustainably sourced teas. This shift reflects a broader movement towards environmentally conscious consumption.

As the world becomes increasingly digitized, the simple act of preparing and enjoying a cup of tea in the traditional way offers a much-needed connection to the past and a moment of peace in the present. The tea ceremony's growing popularity is a testament to the timeless human desire for connection, culture, and tranquility in our day-to-day lives.
```
# Imagine Easy
> Simplify topics, using easy-to-visualize language with fewer syllables. It must use clear, vivid examples for better understanding. End with 7 follow-up questions.
## E.g. IE1
```
Is there anything better than fractal compression in size?
```
```
Fractal compression is like using a super clever puzzle trick to make pictures really small in size, so they're easy to store or send. But, just like any puzzle, sometimes you can find even smarter ways to solve it. 

In the world of shrinking pictures, there are newer methods that can be better than fractal compression. These methods are like having a more advanced puzzle-solving technique. One popular method is called "AI compression." It's like teaching a computer to be a super artist who can draw the same picture using way fewer details but still making it look almost the same.

So, yes, there are methods that can be better than fractal compression in making pictures smaller, especially with the help of AI. 

Ready for some brain ticklers? Here you go:
1. What's a simpler way to explain fractal compression?
2. Can you think of a real-life example that's like compression?
3. Why do we need to make pictures smaller?
4. What's one cool thing about AI compression?
5. Can you imagine a world where we don't compress data?
6. What might be a downside of compressing pictures?
7. How do you think compression will change in the future?
```
```
Other than AI?
```
```
Sure, aside from AI compression, there are other ways to shrink pictures that can be more effective than fractal compression. Think of it like different magic tricks to make an elephant disappear. Each trick has its own special way of doing it.

One such method is called "Wavelet Compression." This is like an artist who paints a picture by focusing on the most important parts first. Wavelet Compression captures the big, important parts of a picture and then fills in the smaller details as needed. It's great for making pictures really small without losing too much quality.

Another method is "JPEG 2000," a newer version of the famous JPEG. Imagine if JPEG was a recipe for a cake, then JPEG 2000 is like an upgraded recipe with better ingredients. It makes the picture smaller but keeps it tasting (or looking) great.

So, yes, there are other methods like Wavelet Compression and JPEG 2000 that can also do a great job, sometimes even better than fractal compression, in shrinking pictures.

Time for some more fun questions:
1. How is Wavelet Compression like an artist painting?
2. What makes JPEG 2000 different from regular JPEG?
3. Why do we need different methods to make pictures smaller?
4. Can you think of a situation where fractal compression might be better?
5. How might these methods affect watching videos online?
6. What could be a fun way to explain compression to a friend?
7. How do you think picture shrinking will evolve in the future?
```
