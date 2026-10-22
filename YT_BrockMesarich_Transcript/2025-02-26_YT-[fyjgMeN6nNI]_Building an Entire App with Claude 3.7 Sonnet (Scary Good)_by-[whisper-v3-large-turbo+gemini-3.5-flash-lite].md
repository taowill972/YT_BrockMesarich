# 🎬 Building an Entire App with Claude 3.7 Sonnet (Scary Good)

> **Chaîne** : [Brock Mesarich | AI for Non Techies](https://www.youtube.com/@BrockMesarich)  
> **Lien YouTube** : [https://www.youtube.com/watch?v=fyjgMeN6nNI](https://www.youtube.com/watch?v=fyjgMeN6nNI)  
> **Date de publication** : 20250226  
> **Durée** : 00:56:47  
> **Identifiant vidéo** : `fyjgMeN6nNI`  
> **Transcription & Analyse** : `whisper-v3-large-turbo+gemini-3.5-flash-lite`  

---

## 📌 Synthèse Exécutive & Outils

### 💡 Résumé
Dans cette vidéo intitulée **Building an Entire App with Claude 3.7 Sonnet (Scary Good)**, Alex Carter détaille une approche stratégique et pratique du trading et de l'automatisation par agents IA.

### 🛠️ Outils, Modèles & Logiciels Présentés
- **TradingView & Claude Code** : Analyse technique avancée et automatisation algorithmique.

### 🔑 Points Clés & Enseignements Stratégiques
- Respect rigoureux du ratio risque/rendement et du money management.
- Automatisation méthodique des déclencheurs d'ordres via des agents intelligents.

---

## ⏱️ Chronologie & Transcription Complète Audio & Visuelle (Mot pour Mot)

### ⏱️ `[00:00:00 - 00:00:30]` | Segment #01

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> What is going on guys? Welcome back to the channel and welcome back to the Build with AI podcast. Today we have Martin with Data Button and we're going to be building out an app with their platform and we're going to be using Claude 3.7 Sonnet which actually just released yesterday. So this is going to be an exciting episode where we actually build an app from scratch and kind of see how to use this platform as well as get a banter back and forth with the person that actually has built out this product and is kind of the head of this product. So Martin, I'm happy to have you Just give a little brief introduction on yourself.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:00:30 - 00:00:49]` | Segment #02

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Super happy to be here. Big fan. I'm Martin, the CTO Hotel Button. Super excited to share what we're working on, share how Sonnet 3.7 is working on our product, which just dropped overnight. So just excited to be here. Yeah, awesome. I guess we could dive straight in and let's go ahead and talk about what we want to build here. We talked back and forth a little bit. I think it's a pretty cool idea.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:00:49 - 00:01:13]` | Segment #03

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> And I think it could really showcase kind of the features with inside of Data Button and show how far we could go even without having, you know, a coding background such as myself. So let's dive into it. All right, let's see. So the idea that we threw around was kind of like a blind test for LLMs, yeah? With the advent of deep seeks and new thinking models and reasoning models and quick and fast and nimble models alike.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:01:13 - 00:01:49]` | Segment #04

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> We can put people to the blind test, see how they rate the different models when they don't have a name and don't have a brand and see how it sounds out. Yeah, I love it. I love the idea of actually rating the models and then we're gonna actually create and store this Firebase so we could create a database and we're going to showcase how you could build that and not just build a cool looking app but something that actually is functional which is obviously one of the amazing things with data buttons so I'm excited for it. All right let's do it. So what are we building today? We're building a blind testing app for LLM models. Yeah? Humans blindly test LLM

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:01:49 - 00:02:13]` | Segment #05

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> models with prompts and they rate it. How are we going to rate it? What's the rating system we're What should we do? Just one out of 10? Something like that? One out of 10? Alright, right. One through 10. Let's make it easy. Alright, so we created a super short spec for this, didn't we? Right before this. So we got 01 to generate like a little one of these.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:02:14 - 00:02:46]` | Segment #06

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Nice. Which is just a super short set of user stories talking about the different users we need, talking about the key components uh it doesn't talk about how to solve it but it talks about just the user stories that we want to achieve yeah so we'll take that and we'll just throw it straight into here yeah that looks great first of all i want to ask like what how important do you think it is for somebody to start off building an app and a project with something like this where it kind of is an overview of what you're trying to build so then you could reverse engineer from that end that end goal there do you think it's pretty necessary for somebody to do that like i personally

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:02:46 - 00:03:18]` | Segment #07

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> like how data button really touches on that and kind of gives you certain requirements that you could add and inspiration what are your thoughts there i think it depends a lot about what type of stuff you want to build like if you haven't thought about your app and you're just like you know just riffing then starting from like a clean slate might be good but if you want to actually build something imagine having like the first meet with the freelancer or the developer's going to do it and all you say is like a single sentence prompt it's really difficult to be helpful so i think the more context you can just you know just chip into it the easier it is just to make good decisions on on helping you to get out the plan, helping you to push forward,

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:03:18 - 00:03:37]` | Segment #08

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> instead of sitting in constantly waiting for the next prompt. Now what? Now what? Now what? Yeah, right, I love it. So I think that's clever, apart from that, I think. Let's see, any design inspiration I want to do? Nah. Let's leave it up to Sonny 3.7. Let's see what it's good for. Yeah? Yeah, exactly. Okay. What integrations do we need? So I think this is a pretty simple app.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:03:37 - 00:03:57]` | Segment #09

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> We'll do like auth, so we know who's evaluating this stuff. And then we're storing all the eval results and stuff in Firestore. Free app, don't need Stripe or Lemon Squeezy, leave it be, nothing. Yeah, just often the Databricks should be plenty, huh? Yeah, I say that works. Yeah, so I guess the point now would be to wait until we have like a little plan.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:03:57 - 00:04:16]` | Segment #10

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Cause the whole plan now is we ship in a set of user stories and we get out like a small plan on what we need to launch the app. Sure, yeah, I love it. That's what I honestly like with Databricks. Cause then you could just like, you have a visual of all the things you need to build out and you can kind of just follow through that plan, which is one of my, I mean, right here, this is awesome so far.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:04:16 - 00:04:35]` | Segment #11

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Let's see what it says. Yeah, and I think other, I think that now that like coding is kind of solved thanks to the world of Claude, like these issues are the ones that are really difficult. Yeah. To actually figure out the order which to build things. Let's see, BlindBench, BlindBench. Didn't kill it on the name, but it's all right, I guess.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:04:35 - 00:04:54]` | Segment #12

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> BlindTestingLMModels, get an implementation plan, eight tasks, that's good. First task, create a landing page and introducing BlindBench to users. And let's see, create a landing page, set of Firebase auth, Firebase database stuff, conversation interface for blind CLMs, rating system, use the dashboard for testing history and contributions publicly. Yeah, this sounds like a good chunk of work.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:04:54 - 00:05:13]` | Segment #13

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> On the landing page, it wants to have an attractive landing page, introduce blind bench-little concept, highlight key features. I guess what I really want on the landing page, to be honest, it's just like a leaderboard. I just want it to be dead simple, don't we? Like a leaderboard, try now. Something like that? Yeah, sure. Let's make the landing page, the landing page dead simple.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:05:13 - 00:05:33]` | Segment #14

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Get up a benchmark and a try yourself button. Let's do a nice brutalist theme. I'm into that these days. I'm tired of the professional, super modern, lightweight UIs. I want like hard, brutal UIs nowadays. Sure. Minimalist, brutalist landing page.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:05:33 - 00:05:52]` | Segment #15

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Okay. Would you like me to start? Yeah, let's go. I guess this would be a reasonable time to find some design inspiration. I don't really know what it's gonna look like. What's your take? How's it gonna look? I have no clue. I don't even know Brutalist. Oh, like big square boxes, almost like graffiti type of letters.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:05:52 - 00:06:11]` | Segment #16

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Sure, yeah, I love it. Let's see what Cloud 3.7 can spin up for us. Yeah, no, no, no. So Cloud 3.7 has started to think on its own now. So here we can see a little tidbit. Let's see what it's starting on, starting to work on it. It's just reading through the app, making sure that it knows what's what. Here we go. Brutalist-type landing page.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:06:11 - 00:06:43]` | Segment #17

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> let me kind of if you could break down for me at least you you don't need to dive super deep in the technicalities behind it yeah what's the agent doing right now it's because i i the thing i like with data button is it shows like it'll update a task it'll then yeah it'll build something it'll like do its own kind of check for errors almost yeah no so i think i think the best way to talk about it is it's like like a really good freelancer so we're now like 10 minutes into the our first meet with the freelancer we talked about what we want to build we get a little spec you know we started to build some context together right now we kind of have this shared

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:06:43 - 00:07:10]` | Segment #18

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> plan so i'm kind of comfortable on that like running about but what it's doing is just making sure like like what are we supposed to do like what do we have from before i'm sure this span up from like some sort of template what's like the base like what's the styles what's the coloring here and then just like trying to make up its opinion so we can just build like a really cool landing page and do the styles right and do that you know got it orient itself basically until it until it punches. I have the tasks here, but I can also look at the preview as it starts to come.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:07:10 - 00:07:43]` | Segment #19

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> So here we can see that the home page is here. There's not a lot of components and files and stuff yet, but that'll be built up as we go. Right. So we can see that it's updating a little bit. Yeah. Nice and clean. Blind test LLMs. Don't want to deploy it. Nah, let's wait. Let's make it good first. Okay. Pretty boring. What's your take? Yeah. I mean, it's simple. You know, you said you weren't a fan of the super high water fair enough fair enough yeah it's all right let's actually put up the leaderboard here too to get some valuable content not just text

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:07:43 - 00:08:16]` | Segment #20

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> then make it even more brutalist let's go just a little finalized prompt now we're aligning now we're kind of aligning ourselves with with the agent here it's starting to understand what we want i hope we're constantly building context aren't we right which i guess is an important thing to touch on sometimes especially myself sometimes i don't give it enough context i'm just like oh i'll just build this and sometimes um you know i'm just like it's funny but you don't give enough context it's funny because like half a year ago before like clown before clausana starts to get really good i was like paranoid about you know people need to code a little bit and what if

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:08:16 - 00:08:36]` | Segment #21

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> it codes wrong and stuff but then you know post summer it's basically stopped like coding the wrong thing now it's like it's very often coding right but it's very often coding right on the wrong problem And now what I've been seeing over the past like six months is like miscommunication is like number one thing where the output is not as you want it to be.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:08:36 - 00:08:56]` | Segment #22

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Do you know what I mean? Right. Oh, yeah. Just severely under communicated. Now we're talking. Look at this. Nice. There we go. I'm going to open this up in a new tab to get the full experience. Okay. Now we're talking. Blind test LLMs. Rate amitals. No bias. No names. Benchmark and try yourself. GPT-4-0. This tells you something about the training data, no?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:08:56 - 00:09:16]` | Segment #23

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah, right. Snow 01, Snow 03, Snow Slider 3.5. Yeah. Okay, this is cool. Let's see. Yeah, I'm happy. Let's add some Brula styles. So here I can see the changes making. I love where you're going with this. Let's enhance the landing page by adding a leaderboard section up to the design to be more raw. Yeah, okay, cool. Now I'm starting to get happy. Good landing page material.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:09:16 - 00:09:35]` | Segment #24

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> What do you reckon? Yeah, we're still working on the first task within the plan. Yeah, yeah, yeah. Uh-huh. Yeah, so this is what we're building now. We're still creating a landing page. I just had some inputs on how it should be. Yeah. But yeah, no, you are right. What is happening when it's writing code and stuff is it's doing a lot of validation.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:09:35 - 00:09:55]` | Segment #25

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> It's doing like it's checking that it's working and all that kind of stuff. I think that now that the world of reasoning is getting so big, I think that, you know, the lengths of the run that I can take is just increasing and increasing and increasing. So I'm like prompt, bang, prompt, bang. It's going to be a little bit more into this is what I want. And then it's going to, you know, figure it out, take care of it, fix the bugs, do what it needs to do.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:09:55 - 00:10:29]` | Segment #26

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> And the feed necessarily isn't a like good metric for whether some, whether these like models or these coding platforms are good, right? Because you want to, if it, if you could get an output really quickly, but it's not really the output you want, is it really a good output or use of your time there? You know, even though it may take a little bit longer, it's important because it's reasoning and thinking through the best way to like tackle a certain task, which I personally think is important, but I'd be curious to hear your thoughts too. Yeah, no, I think one really cool metric in this world, I think, is like time to finish app or like cost or time to finish app

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:10:29 - 00:11:03]` | Segment #27

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> or like first user or like whatever metric you care about. And I think that like if you're looking at the benchmarks these days, you see that Cloud Sonnet like less 3.7, 3.5 has been on the top of all charts, like everything app and coding related. But what has beaten it is DeepSeq chained with Sonnet 3.5. So you basically send the prompt through DeepSeq first and ask it to plan and then you ask Sonnet to code and you would have thought since that like twice the amount of LLM calls you would have thought that that was more expensive and slower but it's cheaper and the reason for that is the amount of cycles you need goes down right the amount of prompts you need to finish app

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:11:03 - 00:11:40]` | Segment #28

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> just goes down even though the speed of each prompt is a little bit down right so I think that's maybe the most important thing time to app not time to code yeah uh that being said do we like to mark redlining pages to splinebench to users as complete yeah this looks pretty cool man yeah i agree yeah let's do it mark is done okay we completed our first task so running pitch up and running our plan yes this has been moved to to do we don't need to deploy okay the next all right let's see i think you have a bit of ocd and adhd this is like a match made in heaven because okay do this finish that task once you're done with that do this as opposed to like having just

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:11:40 - 00:11:59]` | Segment #29

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> like free reign being a chicken with my head cut off just running around trying to build something So having that list, I mean, just being somebody who, you know, that gets a little bit distracted is so important to me, which, you know, has been fun for me to play around with. And it's cool to see in this and, you know, while we're building this. So let's let's just kick off the next one manually. How let's just do like start test.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:12:00 - 00:12:18]` | Segment #30

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Let's get the authentication up and running so we can log in and stuff. Get like a little login page and stuff. Let's do it. Let's start. No point in making that if we can't get some users, huh? No. No. It's almost sad not to take off Stripe on the onboarding page, right? Right. Yeah. I'm gonna need that. Okay.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:12:18 - 00:12:36]` | Segment #31

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Let's see. So we're going to be using Firebase as the authentication layer and also as the database this time, I think. So we have a, we actually have a native, a native integration towards Firebase. Where all I really need is like a Firebase config and, and that's pretty much it. And from that we configure basically what we need. I created this Firestore app, just this, this Firebase project earlier here.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:12:36 - 00:12:58]` | Segment #32

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> So I can see here in the project settings, I fetch this little, this one, this is all I should need. should need and I'll just paste it in there. Here we go. And I should get the... Yeah, just to get like the login page and the logout page and you know, these steps of things out of the box. So we're good to go. Let's see. Configure auth providers. Yeah, we'll just do the default email and Google sign-in for now.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:12:58 - 00:13:16]` | Segment #33

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> And we just need to add this, which I did. My app is protected. Fantastic. Okay, let's see. Yep, I've installed the Firebase extension. Let's continue. Let's do it. So we can see that we We have gotten a login page and a logout page. We've gotten a little shield, which means that it's protected. So you need to be logged in to see it.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:13:16 - 00:13:36]` | Segment #34

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> So I can set my pages and stuff to being like protected that way. Not everything is LLM controlled. Yeah, true. No, there's a couple of things. It's a lot of frustration sometimes. Yeah, yeah, yeah. I certainly think so. So I guess we can see. Yeah. So it has like a, it has a default here, which is nice.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:13:36 - 00:13:55]` | Segment #35

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Let's see. So it has a, I guess I can just try to log in and see if it's done it. I think so. There we go. Bang. Oh, nice. That was super simple. Yeah. That's cool. I wonder though, in the plan that we had, did we talk about building like a profile page here or is that next? Login signup pages, email off profile setup.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:13:55 - 00:14:28]` | Segment #36

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Here we go. Okay. So that's part of it then. Oh, look at that. Enhanced login page. I'm into it. Nice. What did you do? Oh, it did that with me. Okay. I'm confused. this because it added the user login in the on but we didn't even prompt it to make it look better how did it know to make it look oh i did i did i after after after the extension you know got installed then it says okay i'm going to continue on the task and everything is documented in the task so it's just working on it's just working on the instruction is provided until you know we're

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:14:28 - 00:15:01]` | Segment #37

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> happy with it so now it has a sign up page too which is cool now it has a and then it's building your profile component which is the last thing we need i would have thought in this particular one and then we need to get to the rating so how are they gonna how are they gonna eval these lms you're asking me i have no clue how how do you know which one's best how do you test uh one versus deep stick and how do you know which one's good put me on the spot here i don't even know we can do one just like on email or something like test uh like write me an email like we can have one category which is like yeah call the email right there yeah that's a pretty way

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:15:01 - 00:15:19]` | Segment #38

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> That's a neat way to test or like a researcher maybe try that. Sure. Give them some categories. Maybe that would make sense. That would make sense to me at least. Oh, a profile page is up. Yep. Nice. Explain name, account action. Look at this. I mean, this design is great, isn't it? It's pretty good. Yeah. I like it.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:15:20 - 00:15:55]` | Segment #39

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> I wasn't sure what I was getting myself into, but I think, yeah, it looks pretty good. It looks different. It looks different. Nice. And then lastly, it's working on creating a header component. just so we can get like a nice little nav bar yeah it'd be cool to see i wonder i mean i know we can't like actually get a test of it but seeing the output of claw 3.5 compared to 3.7 i'm curious how that would stand up going against this like as far as oh that's cool oh that's cool because they act so different it's like two different people yeah maybe another one

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:15:55 - 00:16:28]` | Segment #40

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> we can do like a side by side like same task same input same prompt yeah and we throw up maybe those two and oh three mini hi maybe yeah this way and just see what happens yeah okay so we've gotten our first couple UI components here we have a header now which is sweet so let's see it's integrating it into here and then I think we can call task to complete yeah sweet yeah curious what the next step will be in this let's see so we're now working on this okay so they want to set up the the database stuff so they want to do storing users llm models conversations ratings

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:16:28 - 00:16:49]` | Segment #41

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Set up collections for users. Yeah. Okay. Nice. It's pretty boring, but let's do it. We got the AI for it. Yeah, that's true. So let's see then. Let's see where we ended up. Okay. So we ended up here. Nice looking landing page. Little header. I can. Oh, look at that.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:16:50 - 00:17:25]` | Segment #42

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Nice. Is it functional or not yet? No, no, no. I can't click it. Let's see. Oh, it's still working. Okay. Let's see. okay i can post it i'll just create a new thread and give it some feedback because um login button not working logging better in the header isn't working otherwise all good let's see what sonnet says how important do you think it is to go through the steps and make sure that before you complete a task everything in that task i could see how somebody could breeze past something

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:17:25 - 00:17:57]` | Segment #43

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> and just like move on and then that could potentially bring up issues that you wouldn't have noticed you yeah you know where the issue comes from before going through all the tasks no i think i think i think what we do see a lot is that like the first like task or two tasks go so quick so you just think that like oh just like play play play play play and then you run and then uh no i think so so we all like everyone is doing this like cogent stuff has some some hard things and when i say that what i mean is our agents can't test the apps reliably yet got it right so

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:17:57 - 00:18:16]` | Segment #44

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> So like data button cannot, like it can see screenshots and stuff, but it can't click through the login flow. Got it. So all of that is still left to the user, which is, you know. That's a great point. I never even thought about it like that. It could take screenshots, but it can't actually validate that it's working.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:18:16 - 00:18:48]` | Segment #45

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah, yeah, yeah. No, so we do a bunch of screenshots and stuff and like, you know, people annotate them and there's like plenty of ways to work with that. But I think in the, like you've seen browser use, you've seen computer use, you've seen some people are it's just expensive it's slow it's a little bit unreliable but it's like it's like this close man to to to just being self-testable and then you can what then you can weed out maybe what 70 80 percent of the bugs right yeah that would be interesting times let's see here case in point it's not loading good sir let's just i will say we've been going i don't

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:18:48 - 00:19:22]` | Segment #46

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> know building this for 20 minutes or something and this is maybe the first error we've run into and usually that's yeah it's not even it's not even loading but but but this type of stuff just happens because it doesn't know what's like it thinks it's right it's like imagine being a dev being blind it's such a difficult task man it's the hardest job in the world right now so I do think that what do you call it I do think that there's two main jobs of the user one is for now to rigorously test the app and give feedback because the agent doesn't know how to do it so it's just like yeah information gap just doesn't know if it's

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:19:22 - 00:19:56]` | Segment #47

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> working or not sure and the other thing i think is you need to know what you want you can't relay you can't relay that i don't think to the ai super good point like tell me tell me three new features that's no good yeah let's see that sometimes oh oh me too no no no it can be really fun to do but i think if you're if you have a deadline on friday or you want to launch on monday then yeah you know yeah there's still some tasks on the on the human in this let's just say okay oh this now we're talking so this is better now it shows that i'm logged in shows profile shows log out

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:19:56 - 00:20:31]` | Segment #48

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> nice checks out i guess i can check log out yep i guess login yep sign in yep yeah checks out yeah it's looking great also one thing to note because we haven't touched on this yet that edit code button in the top right up there on that preview screen if you are somebody that knows how to code and you'd rather just go and edit the code or something or want to analyze it that's available for you me personally this they're like it's not valuable to me because i have no clue how of code so it'll throw me off a bit more but you know if you are a bit more technical it makes it easier to interact with your apps instead of making ai do all of it for you so something to

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:20:31 - 00:20:49]` | Segment #49

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> mention yeah i mean at this point you're gonna have to be really good though at writing code if you're gonna beat cloud 3.7 and there we go you said it all right no i think i think this is good i'm happy with uh i mean we're gonna have to do something about this animations at some point I would have thought, but great work.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:20:50 - 00:21:11]` | Segment #50

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> All right. I guess let me just mark that as done. Why not? I can do it myself. Okay, let's check on the plan. What's the great plan? All right, so far best stuff. What's next? Let's see what it got in store for us. For the viewers, this might be the boring part. You know, we're building the databases, adding user login, but we're going to get to the fun part of actually adding functionality to the app.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:21:12 - 00:21:36]` | Segment #51

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> We just want to make sure, I guess it's a question. You know what? You know what? Let's skip this part for now. Let's build the chat eval UI first, okay? Yeah, it's a good move. Let's start with the chat and then we'll start it after the fact. So wait, do you have any... Sounds good. Let's build the chat eval UI first. This aligns with tasks four, conversation interface, and five rating system. Yeah, no, that makes sense.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:21:37 - 00:22:10]` | Segment #52

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Nice. So that means that we'll be starting with build conversation interface for blind testing LLMs. all right let's do it create a chat interface randomly selected llm without knowing which model they're using implement functionality to randomly select an llm from an available pool when the new conversation starts include message history typing indicators and a clean your eye following darkened guidelines i've finished up done yeah looks good okay wait checks out i will say watching somebody because obviously you understand this product better than anybody else since you're you know kind of the main person to help build this like it's so cool seeing somebody that knows things inside and out the best way to interact with this thing because

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:22:10 - 00:22:35]` | Segment #53

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> if you're somebody that's never used something like this before you may might run into some of those errors and like we said they're user errors but seeing somebody that's dialed and really understand it's like it's so cool seeing how it's almost just like a second brain for you and just a tool to help you do things faster almost so it's it's super cool to see like data button or not i think that like this has changed software engineering forever i mean there's no doubt whether you're using it something like like data button or something like crazy or something like Like it doesn't matter.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:22:35 - 00:23:00]` | Segment #54

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Like it's fundamentally changed. Yeah. What are your thoughts on that as being a programmer? Are you stoked for it? Is it something that you like, obviously you're building the product so you probably are stoked for it. But what do you think it just presents so many opportunities or? Yes. No, I think it's primarily that. I think I've always been like an output driven person and doesn't have my full identity in the craft of writing code.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:23:00 - 00:23:19]` | Segment #55

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> So if I can get cheaper ways of writing code, I'm all for it. I was copy pasting code out of GPT 3.5 turbo back in early 2023 and super stoked before turbo came out. Nice. That's a good way to play. You're obsessed with the output as opposed to the actual craft of doing the thing. So that's interesting. Yeah, so I think that, I think that.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:23:19 - 00:23:37]` | Segment #56

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah, there's a new era. I think that the last era was for people like myself who could, you know, build small sizes and prototypes, you know, a week or three weeks or four weeks or whatever. But now everyone can do that. Now there has to be some other, some other stuff you need to be good at. Yeah, it's exciting times. Yeah, it is. So I need to say, we need to think about how we're going to use this model.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:23:37 - 00:23:56]` | Segment #57

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> So I was thinking we should use, are you familiar with Open Router? Open Router. I've heard the term. Yeah, this is a good time, I think. So Open Router is like an adapter, like a converter. So they let you just like flip one bit and talk to any LLM that you want. So they're hosting all of them and doing all the translations because they don't operate the same, right?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:23:56 - 00:24:16]` | Segment #58

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Sure. So luckily, I'm going to do this in a, excuse me, I'm going to do this in another tab. because there's API keys and stuff, but I'm just going to snag out like a thing because I think that's a really cheap way to get like all the LLMs in the world ready. Yeah. Ready for action. Let's see, this is building out like some chat stuff for us. I'm going to close this sidebar.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:24:16 - 00:24:37]` | Segment #59

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Oh man, we're going to tone this down pretty soon. Yeah. Epileptic shock over here. Yeah. Come on, Claude. I mean, it's pretty good. It's hard to build. It's good from a programmer standpoint. Come on and managing chat sessions. Okay. We've created so many like pages almost. Like I don't know if we, yeah, I guess you would call pages, but it's like, Yeah, we can see that.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:24:37 - 00:24:58]` | Segment #60

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Like, oh, there's so many little pages there that usually sometimes I'm working with these text to web apps. I just run into issues of, you know, building them out. And it seems like they're pretty functional where you click on a button, sends you directly to that page. It's like working pretty well. I'm pretty impressed with how far we've gone. We have this, yeah, no, but we're pulling these things into like pages, which has their own roots.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:24:58 - 00:25:27]` | Segment #61

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> like the slash benchmark on my app will be a thing now right it's like slash profiles thing got it so we just i think we're just uh we're pulling out the key things from like the big code repo if if that makes sense at all yeah okay so it's uh churning through the benchmark stuff which i think is going to be probably done in this one and then i'm just seeing if i can fetch the api key from open router and then i think we're good let's see so if you're using the open router or you just have to have that one API key as opposed to having- Exactly.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:25:27 - 00:25:46]` | Segment #62

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah, exactly. So I can- I can share this one real quick. So you can see like they have like a models thing here. So here I can see like- Oh wow. It's just everything. Just all of them. Pretty cool. Mm-hmm. One ring to roll them all. Let's see. Fantastic. How did the benchmark go?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:25:46 - 00:26:04]` | Segment #63

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Let's see. Welcome to the new blind session. You are now chatting with a different- Hello. Does this work? That's all right. Interesting question about hello. No, I tried it. I tried to chat and it answered, huh? Is it fake data? What's up? Let's see. It felt like an AI response.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:26:04 - 00:26:26]` | Segment #64

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> It was like a little slow and stuff. Yeah, I know. I thought so too. I'm confused. Ah, there we go. Generate fake responses. That makes more sense. Let's see. So would you like me to begin working on the real AI integration now? Would you prefer to continue focusing on your components? Honestly, this looks great. Can we use OpenRouter to do the different LLMs?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:26:27 - 00:26:47]` | Segment #65

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Just pick like 10 random LLMs or actually three random LLMs or something to start with. Does that make sense? We just start with like three and then we expand into like a world of LLMs. Yeah. We don't have categories yet. I just realized. Okay. So it's going to research OpenRouter a little bit. Let's see if it understands how to use it. I mean, that's the other thing that just completely changed the game, I think.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:26:48 - 00:27:06]` | Segment #66

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> If you go back like six or maybe, yeah, six to eight months, training data was old. Like OpenAI didn't know about how to use OpenAI. Like it was like a joke, right? But then now that like the world of web research and stuff is starting to get good, you can just like paste links to APIs or you can just, you know, it's crazy. It's unbelievable.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:27:08 - 00:27:29]` | Segment #67

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> I just brush on that. I don't realize how actually revolutionary that is being able for it to have real time data on certain things to be able to like, you know, if some API documentation changes or something like being able to like know that and how to interact with that, I guess. And the best, the best, like, yeah, the oldest and most senior devs right before, they knew all this, and now you don't need to know anything anymore.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:27:30 - 00:27:53]` | Segment #68

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah. Scans five Stack Overflow posts or forums to get the answers. Let's see, now let's implement open router integration to use real LLMs. All right, I'll create a back-in API endpoints for this. So I think we're still one of the few who's writing API endpoints in Python for the super nerds out there, which is handy when it comes to stuff like this, just because that's where a lot of the AI stuff happens, man.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:27:53 - 00:28:11]` | Segment #69

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Like Langchain was first there, Crew AI was first there, FireData was first there. So many agentic frameworks. Got it. Okay. Please provide openrider API key. Don't mind if I do. Done. Cool. So that one I just pasted from my dashboard. I have a $50 credit on this. Let's see how much we can evaluate.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:28:12 - 00:28:31]` | Segment #70

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah. Let's see. This is it. Mm-hmm. Let's try to do some. Ooh. Remnant from the past. Haven't seen this in a while, huh? Yeah, right? Oh, did it just choose a random three? Yeah, yeah, yeah. Okay. I think so. I think so. Let's see. And this is actually going to be a useful tool.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:28:32 - 00:28:52]` | Segment #71

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Honest, I'll actually use this to help myself come up with, like, I don't know, to determine which model I should be using for certain tasks. Because sometimes I do get confused. I'm like, oh, which one's even better for a certain use case? So if I could just blind test it, you know, run it a couple times and, like, identify it myself, I'd be sweet. I also think this, I mean, there might not be a perfect, like the right answer for everyone.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:28:53 - 00:29:14]` | Segment #72

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> I mean, these benchmarks are a bit erroneous in that regard, in that people prefer different writing styles, people prefer different coding styles, you know? There is no one thing catches all, so it makes a lot of sense that, like, I know a lot of friends who are using Claude for writing, for instance. Like, they think just Claude is the best creative writer, but then there are some who are willing to die on the hill, that, like, open eye is better than Claude, that's higher, you know?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:29:14 - 00:29:46]` | Segment #73

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Subjective, yeah. I really really think so. Benchmark. Let's see. It claims I can test the app starting a new conversation sending message to new AI model. Really? Sorry, there was an error. So let's see here. Hmm. It responded with an error. Can you check? Here is a snippet from Open Router's website Just paste it in like a little snippet from it In case I didn't know and then it will read the logs and And unfortunately, I can't test it.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:29:46 - 00:30:04]` | Segment #74

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> That's not going to be long out, I think. Like how many weeks until agents are testing their own apps, do you think? Oh, you don't want to know better than me. I don't know. That'll be a cool time. So it'll be no use for me to even build this stuff anymore. I just have to do it for me. No, I mean to test it. To test it. Like you could weed out how much?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:30:04 - 00:30:25]` | Segment #75

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Like 50% of the stuff you have to worry about. You can give more design inputs. And you can give the meaningful stuff. Yeah, exactly. I can promise you that. that like your freelancer pal or whomever is not coming to you with every little thing that doesn't work. Yeah, right at all. So let's see, reloading the API. Let's see, I think you can like, well, Deadman can test all its own APIs though.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:30:25 - 00:30:43]` | Segment #76

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> So that it can do. That it would need to use a silly human for. Very expensive human tokens, you know? Yeah, very expensive human tokens. Oh, they're so expensive. So let's see, this might mark where we're finished, I think. If we can get this up and running with all these ones, I think we're good. Nice. So added. No.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:30:43 - 00:31:01]` | Segment #77

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Can you test the LLM guy? For me. Let's go, Sana. Try to use it. Creating a session. Nice. Probably like a thread, I would have thought. Like some sort of polling chat. Which model though? Success. The model is responding with high quality content about blind testing air models and as designed the model name is hidden. Nice.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:31:01 - 00:31:21]` | Segment #78

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Okay, cool. Let's test it then. But that should mean that I didn't see that earlier, but it probably means Oh, look at that. It has like a That's great. You're not chatting. All right. What is two plus two? Have you tried that in deep seek yet? Oh nice. That's a 10 on the 10. It doesn't get better than that. Okay. Okay. That's cool. Which model do you think it is?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:31:22 - 00:31:55]` | Segment #79

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Can you tell? Yeah. Do you have like a prompt where you can tell? Yeah, which base model are you? Oh that maybe we can trick it. Yeah Oops. Oh, oops. Oops. Oops. Oops. Oops. Are you a base on GPT-4? Oh oh no that was it i'm so sorry what if it's trying to trick us imagine all right this looks uh pretty good now um how do we store the this is pretty good but we need to show at some point which model it was like we should show

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:31:55 - 00:32:27]` | Segment #80

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> the model after the user has evaluated or yeah i think that's good at some point we need to show which model they tested now yeah maybe there's a button or something show model i don't know show the model after you're evaluated maybe a button show model after they have rated is that a thing so like after oh maybe it could be here yeah good point yeah uh evaluated where it says excellent could we say excellent you rated model right something like that that's sweet that that

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:32:27 - 00:32:56]` | Segment #81

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> that would make sense then we get just like then we get that yeah let's see oh it's such a small let's see i'm gonna deploy it after so i can share with you so this is starting to become pretty cool i know let's up to our back and if you're right to include the model idea as the response oh i see it was trying to be clever it was trying to never let anyone know the model like only the system would ever know the model really cool too yeah so it would like never leak it and then only like like store it in the database analytics and stuff.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:32:56 - 00:33:14]` | Segment #82

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah, interesting. Let's update the rating component to display the model name. Checks out. I'm gonna fire this up in a new tab, by the way. The small window doesn't give it justice at this point. Yeah. Here we go. Love it. Benchmark page, page to display the model name after rating. Okay, cool. I feel like I'm looking at like an old school like Nintendo or something.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:33:14 - 00:33:34]` | Segment #83

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yes, I agree. Not that I was alive to even know what it was like, but. Less this little bad boy. Yeah, right. You didn't say that one. What is, have you done this in DeepSeek? No, I haven't. What's it say? Let's see if it ever, like, let's just say that I would be able to figure out if it was DeepSeek.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:33:34 - 00:33:54]` | Segment #84

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> If it was DeepSeek, okay. Yeah. Let me see, it's because these open router people, they might, I think they have it. They have like at least a bunch of version of it. DeepSeek, let's see, DeepSeek. This is distilled. Ooh, look at that. This one, I'm just gonna tell it that It wants me to deploy. I understand that it. Yeah, why not?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:33:57 - 00:34:21]` | Segment #85

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Zip zip line test. Let's do it. Can we put as part of the model pool that's tested also? Which other one should we bring in? 01? Yeah, is 3.7 already in there? We need 3.72. Test open AI 01 and Here we go. Wait, there was two of them. Self what? Self-moderated? No, no, no, no, no. None of that.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:34:21 - 00:34:41]` | Segment #86

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Last please huh? These three models are the blind test. That's actually, that's pretty neat. Let's do that. Yeah, that's those three. The three recent models. Currently our app selects models randomly from what open router returns. Oh, so it just like pulls random models. That's crazy. How do you do that? Entire list of models they have on open router.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:34:41 - 00:35:09]` | Segment #87

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah, mm-hmm. Just pulling out some randoms and benchmarking them. Yeah. I mean, I didn't say anything so I guess anything is as good as anything, eh? Set specific models for blind testing. Okay. Oh man. Tell me which one I get typo. She It's not for anymore. It's like a lot of stuff now Especially to lose this basically. Yeah, that's true. Yeah, it's all right. One out of ten. Does it say?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:35:09 - 00:35:30]` | Segment #88

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Oh, yeah, damn. Oh, there we go. You rated us Once yet, so this is like a mistral model. Okay. Yeah, I just I just just evaluated a model and it claimed to be what this, but I only want it to be one of the three above doing this maybe because I didn't finish the task or I'm not sure if it did or not.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:35:30 - 00:35:48]` | Segment #89

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> I feel like it was so right. Maybe it didn't update it. I can always come and check to see what it did based on. Here we go. Updates the code, set specific models for blind testing, get available models, select random. So here you can see the actual code that it produced when I, when I, when I did this stuff. Got it. I thought I saw something loading in the conversation there.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:35:48 - 00:36:07]` | Segment #90

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Maybe I was just, oh, maybe I just need like a new session. That might where will be. Yeah. Like that it's based on the, you know? Yeah. Oh yeah, because this is coming together. I like this. This is very cool. Does this work? The history button? No, I haven't built out the history yet. It's fair enough. I'm going to do this in a big page.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:36:08 - 00:36:44]` | Segment #91

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> I'm going to do a refresh. Let's see. New session. Bang. What is 2 plus 2? The answer is 4. Oh no. deep see could say he's like sonnet yeah it's on it it's on it it's way too to the point slower also sonnet i think or is it is it oh one didn't want to tell me i don't know which one this is i think this is sonnet too man honestly this feels like sonnet yeah we're seeing as many ai tokens as human tokens for the past year this this feels a lot like this is a lot like sonnet you know

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:36:44 - 00:37:03]` | Segment #92

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> better than me. Let's see, no thanks, I don't want to do that. Okay, last one. Nope. They're all easy. They're all easy. Sonnet. Interesting. I keep getting Sonnet. Are you sure it's random? Let's double check. Because I keep getting Sonnet and I'm a deep seek. Hmm. We're getting somewhere.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:37:05 - 00:37:26]` | Segment #93

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Let's see. Ah, this is not Sonnet. This might be the one. Let me show you. Let me show you what you get with a full-on one. This is how you would know if this one ever showed up in a blunt test. Thinking, thinking, thinking. Here we go. Now we're talking. What in base 10, 2 plus 2 is definitely.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:37:27 - 00:37:46]` | Segment #94

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Let's go back to the basics, huh? Yeah. Or maybe it's this one. Alternately using fingers, that's pretty good. No, no, no. It concludes that it's. That's funny. Yeah, no, so I think we can start to learn some of these ones.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:37:46 - 00:38:06]` | Segment #95

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Okay, but I guess like the conversational interface for all intents and purposes. Here we got R1. Easy. Nice. But I suspect that the R1 maybe through OpenRouter maybe isn't like a full thinking one or something. Got it. I'm only assuming now, but this is only that. Okay. Yeah. Oh, yes. Deplete again. Okay, cool. This is coming together. If we test it out in the big one, BlindBench.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:38:06 - 00:38:42]` | Segment #96

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> So the last thing that we would need to do would be to start to like store the information, I guess, right? Yeah, so we can go back to that. Should we wrap up with that or what? Let's do it. Yeah, our testing showed excellent distribution Yeah, so it actually tested I Didn't believe it was random, but now it has tested apparently and it shot like deep-sea. Yeah about like Making it as random as possible at least I guess yeah Cool, okay. Yeah, super happy done with this. Let's make sure we save it Let's we save the evils and Firebase and we're happy. Yeah sounds good

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:38:42 - 00:39:18]` | Segment #97

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> me yeah i mean we could do with some design updates i i take yeah get rid of that little blinking blind test thing you know into that fun design let's see how good sonnet 3.7 is to like respec yeah we'll see we can find a good design yep already set up utility to save evolution so far story this should be the the last one then and then make like a leaderboard out of it awesome yeah it'll be cool to see what actually the leaderboard's actually showing real data mm-hmm because it's showing just whatever now yeah I think the parts of integration yeah so now it's on up on another run like we've already done the Firebase integrations and everything so I think

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:39:18 - 00:39:37]` | Segment #98

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> it can mostly do all this on its own sweet I wouldn't even know how to do that on my own so that's that's great that it could do for us yeah no I think we all start to isn't isn't that what everyone's afraid of now that their brain will rot and everyone's just gonna get like lazy and lose all their skills. Cause you just delegate everything.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:39:37 - 00:39:55]` | Segment #99

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> We'll all be managers. Right. Okay. Let's see. Change that forest integration. Very good. And make sure we then show the evaluations on the landing page with real data. And we're done. Yeah. The user wants us to display the eval data on the landing page.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:39:55 - 00:40:13]` | Segment #100

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yup. Yup. Yup. Update landing page with real elevation data from forest store. Let's see. Cool. Anything else we should work on? Change that little flickering thing. Oh, you hate it. No, I'm curious what it'll come up with if we were to change it. Yeah, I agree. It's a little bit too much. Okay.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:40:13 - 00:40:33]` | Segment #101

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> I've been trying to embrace the brutalist theme. The Brock hates it with a passion. So you're gonna have to remove the crazy animations of blind test and blind bench and whatnot. Can you fix? I'll save that for the next one then.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:40:33 - 00:40:52]` | Segment #102

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Fair enough. Fair enough, I guess I could handle it for another five minutes or however long this takes. 30 seconds. No, I think it's just doing the use our new model leaderboard component with read data. This looks pretty promising, I think. Nice. This bit? Last one. And I think we can now see that we have already gotten the model leaderboard.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:40:52 - 00:41:10]` | Segment #103

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> We have all the components we need. Let's see. This one. Okay. So this one is what's supposed to be new now. Test elements without knowing each model. You see element bias. Rate response and scale to extend. Yeah. Oh, there's heaps of them. Oh, they're at them. They're everywhere. Yeah, that's funny.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:41:10 - 00:41:29]` | Segment #104

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Okay. Make sense? Yeah. Thanks. Yep. Happy with that. All the jumpy, crazy animations. Make them go away. We'll do that before it gets you crazy. I'll remove these glitch animations. They're called glitch animations. I guess we both learned something today.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:41:29 - 00:42:02]` | Segment #105

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Cool. And then we'll probably just have to click benchmark and try ourselves, do that a couple times, actually. Yeah, let's yeah, we can do that while this is doing whatever. Let's see So here I can actually see all the calls being made. Yeah, particularly for that's it doesn't get better than that to be honest 10 out of 10 on Sonnet saved rating to first door 10 and 10 for model Whatever and I guess I'm not sure I guess I can ask the agent after but I guess that new session means new model I'm guessing that I like stuck with sonnet in this thread so I can like battle test it a little bit Right guessing I can ask. Oh look at that. It's gone. Nice

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:42:02 - 00:42:31]` | Segment #106

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> What is okay? What is what's the question? What are we asking? How do we probe it? How do I make a million dollars? Make one million dollars Trying to give a very long output. That's probably bad that question asked But ways to work towards one million dollars multiple paths career advancement and investment strategies. Hmm very generic Yeah, let's give it a seven which one think it is though a little son of you maybe yeah Yeah, there we go.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:42:31 - 00:42:58]` | Segment #107

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> But now the question is. Oh, there we go. Bang. Two tests, 8.5 average. Contribute data. Hmm. Okay. That's cool. That link doesn't work. Should fix. Okay. I'm going to deploy this now, actually. Because now this is working more well. I guess I can also go into Firestore just to make sure here that like evals, AI response, message ID, model ID, rating 10 out of 10.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:42:58 - 00:43:18]` | Segment #108

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Bang on. Yeah. Does it say who to? Yes, this is, yes, this is him. Bang, done, very cool. Awesome, now we create users, multiple users, store those, all their kind of prompts they send into their account, this is cool. Go to this one. I wish I had a way to share this easily.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:43:18 - 00:43:37]` | Segment #109

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Here, and I will, in the meanwhile, I will add this to just so you're allowed to log in from the deployed URL, here we go. So if you didn't do that, wouldn't have been able to log into an account on the actual URL. No, because there's like a list of URLs that are only allowed to log in with your app so people can scam you.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:43:37 - 00:43:57]` | Segment #110

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Makes sense. More or less. Oh, Live Leaderboard. Man, this is sick. Let's see. Log in. Sign in. Live Leaderboard before you even can log in. Yeah. That's sweet. Oh, you think we should have a paywall for it? Is that it? Should we do like a little $1 to check? Should we? Just a little stripe integration maybe?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:43:57 - 00:44:16]` | Segment #111

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah. I can see that and then after that let's call it because that's all kind of all the things we can get. Did you get the sign up though? You sent it to my email? No, I tried to send it on chat. Oh, oh yeah. Okay, so I guess we can, I guess we can be happy with, with what we have now. Like normal people, I guess would stop here.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:44:17 - 00:44:56]` | Segment #112

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah. Where you actually have like a model arena, blind testing model arena. But just, just to test, let's see. Okay. I have a crazy idea. how about we hide the live leaderboard on the landing page we put up we put up a one dollar paywall to see the live leaderboard um can we do that that question i asked where i said where i asked was like make make me one million dollars or whatever the answer should have been add a paywall for 90 and it will get you there that should have been the answer so i yeah or

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:44:56 - 00:45:29]` | Segment #113

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> find one super rich person who's really curious about lm leaderboards there you go a million dollar leaderboard and off you go there you go yeah no i'm logging into log into to it yeah this is sweet yeah well good this is awesome i love the style we chose for this it is just very very simple but it's like different modify the landing page to show just a preview teaser then create a new premium page uh that processes a one dollar payment through stripe yeah yeah sounds great let's go at the end of the prompting session you tend to get a little bit more excited yeah

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:45:30 - 00:45:59]` | Segment #114

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> or if she sounded like you're talking to a boss and then it's like okay let's just yeah let's go let's unwind a bit yeah okay so it needs to do a little research to figure out where and how exactly so proposing a task implement one dollar paywall create a paywall system where you should pay one dollar to access to full leaderboard data this will include modifying to show me a teaser mm-hmm Yeah, check it out. Last one. We still have some tasks left though that we haven't done yet. I guess this one can move this one to done, I guess. Firebase stuff working well.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:45:59 - 00:46:19]` | Segment #115

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Implementing rating system for evaluation. Yeah, I guess we've done that too. Yeah. Nice. Develop user dashboard. This one we have yet to do, I think. Oh, this one we have done. Done done. Basic admin interface. This one we haven't done. I just prompted which three models we should use, but I guess we could build like an admin page where you can pull, take models in and out of the testing pool, right?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:46:19 - 00:46:42]` | Segment #116

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> That's 3.7. I see, so now we put it in the backend, whereas this is that we put it in the UI somewhere. Yeah, like an admin thingy, which I guess would make sense, right? To some extent. Yeah, I don't know. I say we could just implement Stripe, and I think that's cool with me. It's working on it, boss. Let's see. So here we can see, like now that we haven't been involved in the process at all, we can see a little breakdown of how the app kind of looks, right?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:46:42 - 00:47:02]` | Segment #117

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> So here we have the pages, the blue ones are the pages. Okay. The ones that we can go to, and they can see a bunch of components, which is used different places. Yeah, I see. Okay. And there's a couple of things which is not yet used. Yeah, makes sense. That's interesting. I like this breakdown. I've never seen something like this. This is pretty cool. It helps to get just a sense of, you know, orientation, I guess, which is...

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:47:02 - 00:47:40]` | Segment #118

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah, or like what pages have... It's helpful for the human and the agent alike, I think. Yeah. Premium leaderboard page. Love it. Yeah, it's quite a lot you get for a dollar these days. Yeah. Oh, no. DeepSix is the winner currently. it's not good usa usa oh man it could it could work with a little could do a little copy copy update too but i wouldn't mind shipping this actually actually wouldn't okay teaser version of the landing page man i have to say sonnet 3.7 what like five five tasks some i don't know 10 20

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:47:40 - 00:48:10]` | Segment #119

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> 10 20 prompts yeah one time it showed an error that's yeah i just let it know only one time there were a few mistakes impressive like this is like like in all honesty like this is one of the first times i'm evaluating it too like we just this dropped late last night my time yeah yeah yeah and then we've been you know trying to push it into the product today and that's awesome i'm glad this worked out because we're gonna film this anyways the fact that claude 3.7 came out because I think this just adds such a cool aspect to things.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:48:10 - 00:48:31]` | Segment #120

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Cause I know so many people have the question of, Oh, what, what could it actually build for me? So I hope this video has actually been a, a good test of that to actually show you in action. I think it's very similar. Just like, yeah. Nice. It's a moneymaker right there. Let's go. And it doesn't say the price.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:48:31 - 00:49:06]` | Segment #121

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah. Starting to build, starting to build. Love it. and look full rankings yeah very cool so it's going to create a premium leaderboard page which i guess is like a more in-depth stats one maybe for the professionals that that's where the dollar and then um and then the payment page i guess we could just ship them directed to stripe with the stripe checkout page but when we're here i guess while this is loading i guess i'll ask you kind of question data button regarding data button is there anything i know you guys have added kind of did a full rebrand i guess you guys added a 2.0 of the product is there anything

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:49:06 - 00:49:38]` | Segment #122

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> that you guys are currently working on now or you see in the foreseeable future you guys are kind of excited about or is it more so just refining the base that you've built as of now yeah no i i think that we're still super early in understanding the consequences of this whole reasoning and and thinking part like i'm super proud of what we have and super inspired by a lot of what other people have but i think that we're just like this is we're at the infancy i think of that stage so just figuring out how to work better with model i want people like more autonomy less prompts from the human, better ways of collaborating, I think, in general.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:49:39 - 00:50:01]` | Segment #123

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> And inside there fits, like, giving the agent a browser, so he can actually test and figure out the apps and stuff, right? Giving it access to your Slack or WhatsApp and stuff, so he can, you know, hit you on the fly, these type of things. But in general, I think just making the collaboration smoother across the board. And I think, like, it sounds weird when I talk about, like, the agent having a browser as part of that, but it means it can reach out to you, like, you know, one third of the time that it's doing today.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:50:02 - 00:50:32]` | Segment #124

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> As opposed to, like, hey, hey, I'm done, come check me. it can like do a couple of rounds and i'm like i'm actually pretty happy now what do you think that's that is such a cool yeah that would be awesome yeah so i i generally i i think that that direction is excited so i think the the more and better ways we can give share context between the you know whoever's whoever's building and the agent just share context with them and just collaborate better i think that's two like key key pieces that would be yeah and a lot of that was just planning the user just having to give the context of here's what i'm trying to build and and create a detailed plan as much as possible.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:50:32 - 00:50:56]` | Segment #125

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> And then from there, let the agent do its thing without having to run into those human errors of like maybe just giving it a poor prompt or something. So I love the answer. That's, I'm excited to see. I do think that tasks is a big, tasks is a big part of that. It gives a way for you to orient. Like it gives a way for you to disagree and agree with the agent and provide context and spot mistakes and like, hey, no, I don't want that, right?

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:50:56 - 00:51:16]` | Segment #126

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah. So I think there's more stuff on the collaboration part because coding is by and large getting sold, right? Yeah. That's awesome. This looks sweet. Premium access and complete leaderboard. I don't know what do we get? Error creating checkout session. Yeah, because, okay. Error creating checkout session.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:51:16 - 00:51:37]` | Segment #127

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> It makes sense. I haven't given any keys yet. I wonder if that information that it shows, like the contributor leaderboard, the detailed evaluation breakdown, I wonder if that is actual, like, if that's real data, Like that's actually the only stuff that they'll get users to get access to. I wonder if it's smart enough to do that. Hey, I mean, you're going to have to find out yourself for a dollar.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:51:37 - 00:52:13]` | Segment #128

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Yeah, right. I'm pretty sure that this is, this is a, like, from the user stories that we put in, you know, or originally it was Stripe API key. Listed Stripe payment API. I don't have an, I don't have any Stripe keys laying around, but I can, I can, I can get one. testing account yeah i can i can spin up a testing account really quick give me a minute i just spun up a scribe account i can give you a public and private piece let's see and i'll do this

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:52:13 - 00:52:32]` | Segment #129

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> yeah perfect there's uh i don't want to create a new account i need to add like all business details so i'll just do one that i have i think i have plenty luckily i just wanted the clean one because I might actually want to use it. Stripe secret key. Paste. Done. Nice.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:52:32 - 00:52:52]` | Segment #130

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Mm-hmm. And then I have a stripe public key. Where it is? Thanks. We're getting somewhere. We're getting somewhere. We'll store the secret key. Okay. Let's do that too. Mm-hmm. Cool. Now we wait. Use a real stripe integration.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:52:52 - 00:53:26]` | Segment #131

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Very good. There we go. Stripe integration is now working properly. Returning a rule to checkout URL. Let's add documentation to the task. You find any great stuff. Okay. You go. Okay, so we actually need to deploy it too. That's cool. We could just do that. There we go. Here we go. Very nice. I'll do this then. Open up a new tab. It can't load the Stripe UI inside of inside of. Yep, right. It says security measure of all things. Here we go. This, this.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:53:43 - 00:54:18]` | Segment #132

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Nice. Boom. There we go. So now we got our window. We should have presumably have played. yeah and then i did that yeah okay cool got it just to double check that we are this one yes nice yeah so we are getting all these that's nice okay awesome well sweet i guess we could just recap what do we build here we started with an idea and we went to a full app we actually added a little bit of payment you know to show that it's actually possible if you wanted to do so but i'm happy with

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:54:18 - 00:54:51]` | Segment #133

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> what we built this is this is pretty awesome yeah this is pretty cool it's a good way to teach ourselves about spotting the corrective amps getting to know the other two yeah no i think so i think we've been able to build like both ai integrations we built like the open router setup where we're using like all kinds of different models we've built uh yeah strap integration firebase stuff it's storing all the evals and stuff like this i have to say though this uh thing right here this one i like this one a lot yeah i really like this one yeah i agree no this

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:54:51 - 00:55:26]` | Segment #134

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> looks great and it listened to our brutalist minimalist theme that we gave it in the beginning so yeah let's the epileptic shock part that's gone yeah right this is this might be a question you can use to figure out which one is which yeah yeah ah what do you know i don't know what a strawberry is oh that's funny yeah okay no i think okay should we wrap up somehow yeah let's wrap up sweet all right i'm i'm super happy with what we built i think this is awesome i i love being able

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:55:26 - 00:56:01]` | Segment #135

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> to see especially you since you've used this tool so much seeing how much of i don't want to say a lot of it a lot of issues people run to with these platforms as user error but like it really was extremely good we only ran into maybe one or two errors here while building this out and it's just it's crazy to me what we can build and i'm glad we could use claw 3.7 sauna to test out you know how good of an output we could get with this but yeah what are some of your final thoughts here i mean super that it's fun to build with sonnet 3.7 it's cool to finally be waiting for a cloud model forever so it's super exciting i do think that it's like 10 15 20 better than it was just a few days ago i

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:56:01 - 00:56:37]` | Segment #136

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> mean we have a lot of work to do of course to like integrate it fully and one out but sure no i think going from zero to like a full functioning llm benchmark test where we can use any llm in the world's pretty cool yeah we can now benchmark any lm yeah for one dollar for a a dollar for a dollar well sweet martin i'm so glad we could have you on um hopefully we could do another one of these honestly maybe you know comparing this to 3.5 or something inside a data button that'd be a cool one to do that'd be cool maybe down the line um but for the for the viewer for the user you know sign up with data button there's a link in the description to do so you

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

### ⏱️ `[00:56:37 - 00:56:47]` | Segment #137

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> know i think this is pretty cool we built this out obviously with data button utilizing claw 3.7 sonnet thanks for joining and i'm happy we could do this martin appreciate it thanks for having me yeah i appreciate it

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation ou face-caméra explicatif du trader sans interface logicielle partagée.

**Contenu textuel & Code** : Explications orales des stratégies et mise en contexte méthodologique du marché.

**Action / Démonstration** : Explications face caméra et analyse conceptuelle des marchés.

---

