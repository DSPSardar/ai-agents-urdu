# AI Agents Glossary — Urdu aur Roman Urdu

Har entry: **English istilaah** · اردو · *Roman Urdu* · ek line mein kya hai.

Tool ke naam tarjuma nahi kiye gaye. `MCP`, `API`, `token` — ye English hi rahenge, kyunke
screen par aap ko English hi likha milega. Tarjuma samajh ka hai, naam ka nahi.

---

## Bunyadi lafz

**AI Agent** · اے آئی ایجنٹ · *AI ejent*
Ek program jo khud faisla karta hai ke agla qadam kya hoga. Chatbot sirf jawab deta hai;
agent kaam karta hai — file kholta hai, API call karta hai, phir dekhta hai kya hua.

**AI Employee** · اے آئی ملازم · *AI mulaazim*
Ek agent jisay ek asli naukri di gayi ho: naam, kaam, hudood, aur jawaabdehi. Farq technical
nahi, tanzeemi hai — AI Employee ke paas job description hoti hai.

**LLM (Large Language Model)** · بڑا لینگوئج ماڈل · *bara language model*
Wo model jo agle lafz ka andaza lagata hai. Claude, GPT, Gemini sab LLM hain. Agent LLM
*nahi* hai — agent wo nizaam hai jo LLM ko tools ke saath chalata hai.

**Prompt** · ہدایت / پرامپٹ · *hidaayat / prompt*
Jo aap model ko likh kar dete hain. Agent ke liye prompt hukm nahi, **naukri ka bayan** hota
hai.

**System prompt** · بنیادی ہدایت · *bunyaadi hidaayat*
Wo prompt jo har guftagu se pehle lagta hai aur hamesha lagta hai — agent ka kirdaar aur
hudood yahin likhe jaate hain.

**Context** · سیاق / کونٹیکسٹ · *siyaaq / context*
Wo sab kuch jo model ko is waqt nazar aa raha hai: aap ka prompt, pichli baatein, aur jo file
aap ne di. Context mein na ho to model ke liye wo mojood nahi hai.

**Context window** · سیاق کی گنجائش · *siyaaq ki gunjaaish*
Context ki hadd. Is se zyada daalein to purani baat girti jaati hai — agent ka "bhool jaana"
asal mein yahi hai.

**Token** · ٹوکن · *token*
Text ka tukra jis mein model ginti karta hai. Ek lafz aam taur par ek se do token. Qeemat aur
hadd dono token mein naapi jaati hain.

**Tool / Function call** · آلہ · *aala / tool*
Koi kaam jo model khud nahi kar sakta aur baahar se karwata hai: email bhejna, database
parhna, hisaab karna. Agent ki saari taaqat tools se aati hai.

**MCP (Model Context Protocol)** · ایم سی پی · *MCP*
Ek khula mi'yaar jis se agent bahar ke tools aur data se ek hi tareeqe se jurta hai — har
tool ke liye alag code likhne ki zaroorat khatam.

**Agent loop** · ایجنٹ کا چکر · *ejent ka chakkar*
Soch → kaam → nateeja dekho → phir socho. Yahi chakkar agent ko chatbot se alag karta hai.

**Memory** · یادداشت · *yaad-daasht*
Jo agent guftagu khatam hone ke baad bhi yaad rakhta hai. Context aur memory alag cheezein
hain: context aarzi hai, memory mehfooz.

**RAG (Retrieval-Augmented Generation)** · ریٹریول · *retrieval*
Jawab dene se pehle apne hi documents mein se mutaaliq hissa dhoond kar context mein daalna.
Is se model naye data par baat kar sakta hai.

**Embedding** · ایمبیڈنگ · *embedding*
Text ko aisay numbers mein badalna ke milti-julti baat ke numbers bhi qareeb hon. Isi par
search aur RAG chalte hain.

**Vector database** · ویکٹر ڈیٹابیس · *vector database*
Wo database jo embeddings mehfooz karta hai aur "sab se milta-julta" dhoondta hai.

**Hallucination** · من گھڑت جواب · *man-gharat jawaab*
Jab model purey aitmaad se ghalat baat likh de. Ilaaj: usay source do (RAG), aur jawab ka
source maango.

**Temperature** · ٹمپریچر · *temperature*
Kitni be-tarteebi. Kam = wohi jawab baar baar, zyada = mukhtalif. Kaam wale agent ke liye kam.

**Fine-tuning** · فائن ٹیوننگ · *fine-tuning*
Model ko apne data par dobara train karna. Mehnga aur aksar ghair-zaroori — pehle prompt aur
RAG theek karein.

**Multi-agent system** · کئی ایجنٹوں کا نظام · *kai ejenton ka nizaam*
Kai agents jo mil kar ek kaam karte hain, har ek ka apna daira. Faida: safai. Khatra: ek ka
masla doosron tak phailta hai.

**Guardrails** · حدود · *hudood*
Likhi hui hadd: agent kya nahi karega, aur kis mod par insaan se poochhega.

**Human in the loop** · انسان بیچ میں · *insaan beech mein*
Wo nuqta jahan agent rukta hai aur manzoori maangta hai — paisa, waada, ya kisi customer se
baat se pehle.

**Takeover** · انسانی مداخلت · *insaani mudaakhlat*
Jab insaan guftagu apne haath mein le le. Kitni dafa takeover hua, yahi AI Employee ka asli
score hai.

**Idempotency** · دہرانے پر محفوظ · *dohraane par mehfooz*
Ek hi kaam do dafa chale to nateeja na badle. Agent dobara koshish karta hai — bagair iske
customer ko do dafa order chala jaata hai.

**Latency** · تاخیر · *taakheer*
Jawab aane mein kitna waqt laga. Customer ke saamne wale agent ke liye sab se zyada ahem
cheez.

**Rate limit** · حد رفتار · *hadd-e-raftaar*
API aap se kitni dafa fi minute baat karegi. Isi par aksar pehla agent toot'ta hai.

**API key** · اے پی آئی کی · *API key*
Aap ka raaz ka password. Code mein kabhi na likhein, GitHub par kabhi na bhejein —
environment variable mein rakhein.

**Environment variable** · ماحولی متغیر · *maahauli mutaghayyir*
Code ke bahar rakhi hui qeemat (jaise API key) jo chalne ke waqt milti hai.

**Deployment** · تعین / ڈیپلائے · *deploy karna*
Agent ko apne laptop se nikaal kar ek live URL par chalana, taake wo aap ke bagair bhi chale.

**Webhook** · ویب ہُک · *webhook*
Ulta API call: koi doosra nizaam aap ke agent ko khud khabar deta hai ke kuch hua hai.

**Evaluation (eval)** · جانچ · *jaanch*
Tay-shuda misaalon par agent ko chala kar naapna ke wo theek hai ya nahi. Bagair eval ke
behtari sirf andaza hai.

---

Koi entry behtar ho sakti hai? Issue khol dein — Urdu technical vocabulary abhi ban rahi hai
aur ikhtilaaf jaiz hai.

Maintained by Digital Services Program · https://www.digitalservicesprogram.com/
