# 👾🎯 `Windows Terminal Configuration`

## [Watch YouTube Video](https://www.youtube.com/watch?v=R9Q_y7K03jE)

This is my personal configuration for Windows 11 [Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=da-dk&gl=dk). Due to many requests on my [Programmer Network Twitch Stream](https://twitch.tv/programmer_network), I have decided to export the configuration and share it with those who want to replicate it.

![Windows Terminal](/assets/images/terminal.png)

I'm running all of my services inside the [WLS](https://learn.microsoft.com/en-us/windows/wsl/install). I'm not running anything natively on Windows. While this won't matter much to you, even if you are running e.g. Windows Prompt or Windows Powershell, it's worth mentioning it, as I'm also running Zsh and tmux, which I don't think you can run inside Prompt/Powershell.

In order for the configuration to work properly, make sure to merge your configuration with mine. That means that you shouldn't import the _profiles_ part of the JSON, as they will be different on your computer. With that said, I have actually removed _profiles_ from the provided JSON, as what you might have configured on your PC most likely differs completely from my own configuration.

## Install

- Open Windows Terminal

![Windows Terminal Settings](/assets/images/terminal-settings.png)

- Click on the arrow pointing down, and then on Settings (As shown on the screenshot)

- Then click on `Open JSON file` in bottom left corner

![Windows Terminal](/assets/images/terminal-config.png)

- At this point, you don't want to replace the whole configuration, but instead, keep your `profiles` object in there, and merge it with the configuration I provided.

## Notes

This configuration is mainly for Windows Terminal. It doesn't include my [Zsh](https://ohmyz.sh/) or [tmux](https://github.com/tmux/tmux/wiki) configs. If you haven't already, I'd highly advise you to setup those, or at least, [Zsh](https://ohmyz.sh/).

You can [set it up](https://ohmyz.sh/#install) easily, as the bash script starts the CLI _wizard_, where you simply have to finalize couple of steps. If you want to get some inspiration or help, you can also take a look at my other repository, [iterm2 with ZSH](https://github.com/agjs/iTerm2-with-ZSH). It talks about Zsh, tmux and more.

That should be it!

Cheers
