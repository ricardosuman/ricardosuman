```elixir
# about_me.exs

defmodule Engineer do
  defstruct name: "", age: 0, role: "", nationality: "", languages_spoken: [], expertise: [], tools: [], favorite_languages: []
end

defmodule Main do
  def run do
    user = %Engineer{
      name: "Ricardo Suman",
      age: 29,
      role: "Software Engineer",
      nationality: "🇧🇷 🇮🇹",
      languages_spoken: [
        {"Portuguese", "🇧🇷"},
        {"English", "🇺🇸"}
      ],
      expertise: ["Fullstack", "AI", "Game Dev"],
      tools: [
        {"Fullstack", ["Next.js", "Remix", "NestJS", "Express.js"]},
        {"AI", ["TensorFlow", "LangChain", "CrewAI"]},
        {"Game Dev", ["Unreal Engine 5", "Bevy"]},
      ],
      favorite_languages: ["Rust 🦀", "Elixir ⚗️", "Swift 🍏", "C++ 💾"]
    }

    IO.inspect(user, pretty: true)
  end
end

Main.run()
```

<!--<img src="https://github.com/user-attachments/assets/1537554e-6389-466a-8d4e-12f90d619697">-->
<img src="https://github.com/user-attachments/assets/d60ea55b-9d57-4832-8e2e-c352c4e26da0">
<!--<img src="https://github.com/user-attachments/assets/f4cabbb3-2c1c-4fca-becd-c2ef3538ba97">-->
