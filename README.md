# 2-git-practice — Shaf Khalid

## Interesting Read
**The Twelve-Factor App** — https://12factor.net/

### Why this stood out to me
I like how the twelve factors give a simple checklist for building software that’s easy to develop, deploy, and scale. The ideas are opinionated but practical: declare dependencies explicitly, store config in the environment, keep dev/stage/prod as similar as possible, and treat logs as event streams. These habits reduce “it works on my machine” problems and make CI/CD smoother.

What I found most useful for student projects is how the factors nudge you toward clean boundaries: stateless processes, disposability, and one codebase per app. Even small apps benefit—spinning them up, tearing them down, and collaborating with teammates becomes predictable. It’s a short read with a big impact on how you structure projects.

### Comment by Saad Iftikhar
I appreciated how the Twelve-Factor App methodology emphasizes clean separation of config, stateless services, and portability across environments.  
For students learning DevOps, the principles of disposability and treating logs as event streams map perfectly to modern CI/CD pipelines and make debugging easier.

