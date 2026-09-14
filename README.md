```elixir
# about_me.exs

defmodule Engineer do
  defstruct name: "", age: 0, role: "", nationality: "", languages_spoken: [], expertise: [], tools: [], favorite_languages: []
end

defmodule Main do
  def run do
    user = %Engineer{
      name: "Ricardo Suman",
      age: 30,
      role: "Software Engineer",
      nationality: "🇧🇷 🇮🇹",
      languages_spoken: [
        {"Portuguese", "🇧🇷"},
        {"English", "🇺🇸"}
      ],
      expertise: ["Fullstack", "AI", "Game Dev"],
      tools: [
        {"Fullstack", ["Next.js", "Remix", "NestJS", "Express.js", "React Native", "Swift"]},
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
<!-- <img src="https://github.com/user-attachments/assets/d60ea55b-9d57-4832-8e2e-c352c4e26da0"> -->
<!-- <img width="1024" height="329" alt="unnamed2" src="https://github.com/user-attachments/assets/36eb3833-d2b6-45a3-8cf8-456d12c6a453" /> -->

<!--<img src="https://github.com/user-attachments/assets/f4cabbb3-2c1c-4fca-becd-c2ef3538ba97">-->

<!-- new -->
<!-- <img width="1200" height="400" alt="Mask group" src="https://github.com/user-attachments/assets/efd23216-0f29-44ad-a2f1-536ceef28932" /> -->

<!-- <img width="1200" height="400" src="https://github.com/user-attachments/assets/84698a32-0c87-48ee-9942-47f6bf8f5f25" /> -->

<!-- <img width="1200" height="400" src="https://github.com/user-attachments/assets/13233a74-cfe9-4fbb-b6c0-96fccf7e91c9" /> -->

<img width="1200" height="400" src="https://github.com/user-attachments/assets/7c3bd31d-2436-433d-8509-bd1362862b8b" />

