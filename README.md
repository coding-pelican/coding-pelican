# 👋🏻 Hey, there! I'm Gyeongtae Kim

> **[🔗 Accessible Version](./README.a11y.md)**
<!--
[Accessible Version for Users with Accessibility Needs]
-->

## 💬 About Me

```c
let coding_pelican = SWEngineer_init(create$(SWEngineer_Config,
    .allocator = allocator,
    .behaviour = PelicanLike_behaviour(create$(Behaviour_Params,
        .name = Str_l("Gyeongtae Kim")
    )),
    .hobby = Str_l(
        "📸 Photography"
        "🏃 Running & Jogging"
        "🗣️ Learning languages"
    ),
    .main_domain = Str_l("Game Engine Development"),
    .skills = create$(SkillList,
        .languages = {
            c, c_plus_plus, c_sharp, zig, rust, go, python, own
        },
        .engines = {
            unity, godot, own
        },
        .tools = {
            git, vscode
        }
    ),
    .special_skills: Str_l(
        "🐢 Proud owner of an epic tech neck"
        "🦖 Cheers every time code execution speeds up by 0.01 seconds"
        "🏆 On a record-breaking caffeine-free streak (since 2022-09-05)"
    )
));
defer_(SWEngineer_fini(coding_pelican));

try_(List_append(
  coding_pelican->favorite_foods.base,
  Food_init(Str_l"🍕Pizza")
));
try_(List_append(
  coding_pelican->favorite_foods.base,
  Food_init(Str_l"🐔Chicken")
));

for_slice (coding_pelican->favorite_foods->items, food) {
    IFoodEatable_eatFood(coding_pelican
        ->behaviour.base, food);
}

// output:
// 'Gyeongtae Kim' swallows '🍕Pizza' without chewing!
```

## 📫 Contact Links

- 📧 **Email:** <codingpelican@gmail.com>
- 💻 **GitHub:** [https://github.com/coding-pelican](https://github.com/coding-pelican) - My GitHub profile for open-source projects and contributions.
- 📝 **Hashnode:** [Gyeongtae's Blog](https://dasae.hashnode.dev/) - Read my technical articles and tutorials on various programming topics.
- 📷 **Instagram:** [@dev.dasae](https://www.instagram.com/dev.dasae) - Follow me for behind-the-scenes glimpses of my projects and personal life.
- 💬 **Threads:** [@dev.dasae](https://www.threads.net/@dev.dasae)
- 🐦 **X(Twitter):** [@dev_dasae](https://x.com/dev_dasae)
- 🎮 **itch.io:** [Dev.Dasae](https://coding-pelican.itch.io/) - Check out my game development projects and releases.

## 📖 Story?

<details>
<summary> 🎮 My Journey: From a Curious Boy to a Game Engine Developer</summary>

### 👦 Once Upon a Time...

There was a young boy with unusual hobbies: DOS game emulation and game localization. He was quite the geek, though he didn't realize it at the time.

One day, curiosity struck him. Instead of developing games within a game development environment, he wondered what it would be like to develop games in the real world.

His best friend encouraged him, "Just give it a try!"
"Why not! Let's do it!" he replied. He stumbled upon a Java-based block-coding app and began his journey into game development.

That young boy, once filled with dreams, is now an engineer who develops his own game engines.

What happened in between? Keep reading to find out!

### From "I'll Make Everything Myself!😆"

> "Who needs a game engine to create a fun game?
> I can create fun games even without a game engine!"
> — The past me

This statement isn't entirely wrong.
The boy disliked dependencies and wanted to build everything from himself.

He actually made a pretty fun game, his first project titled 'We are Going'.

It was fun but full of issues, as you'd expect from a first project:

- 🐌 "A text adventure game dropping to 16 FPS?"
- 🌪️ "The UI elements are flying around!"
- 🤷‍♂️ "All the play story logs are gone!"

### To "I'll Create to Understand Better🤔"
<!--
### To "I'll Create What I Needed to Better Understand🤔"
-->

> "What I cannot create, I do not understand."
> — Richard Feynman

Overwhelmed by bug reports and the worst performance issues across multiple projects, he realized he needed a solid foundation and systematic approach to create stable, high-performance games that could bring his ideas to life.

- He learned half of C (it was harder and less fun than Java).
- Developed simple mini-games (a top-down shooter and a Super Hexagon clone) with Godot.
- Learned C# and Unity.

Feeling stagnant in his learning, he ventured into non-game domains, exploring various languages and frameworks to expand his knowledge.

He faced a common challenge: lack of foundational knowledge, leaving many concepts unclear.

- He delved into algorithms and data structures.
- Studied C++ and participated in informatics Olympiads and various programming competitions.
- Sought to understand computers and paradigms, grasping about memory management and diving into fundamentals of CS, English, discrete mathematics, and programming.

By connecting these dots and revisiting C, the scattered puzzle pieces finally fell into place.

True understanding.
He realized that by directly working with concepts and building things himself, he could gain insights and integrate background knowledge more effectively.

He began to enjoy developing high-quality software more than just high-performance games.

Through numerous collaborations and freelance work, delivering quality softwares to clients became a source of joy, extending beyond just his own games and projects.

### 💻 Technical Perspective

While my main domain remains game development, my approach has evolved.
I still want to create great game software.
Often, this involves using existing game engines,
which led me to build my own.

Understanding the "black box" of game engines is,
I believe, The path to creating great software.

</details>
