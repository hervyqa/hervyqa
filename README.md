# Profile

> [!NOTE]
> This **deprecated account**, currently i moving git hosting to
  sourcehut [https://git.sr.ht/~hervyqa](https://git.sr.ht/~hervyqa).

I'm an [obsd] user, software developer, technical
writer, and designer with a strong interest in privacy, security, and
low-level programming on UNIX-like systems. Over the years, I've worked
extensively with Linux and BSD operating systems, including developing
and maintaining a Linux-based distribution for more than a decade.

I actively contribute to Free and Open Source Software (FOSS) projects
and enjoy exploring minimalist, keyboard-driven workflows.

> I am not here because I am different.
> I am here because I exist.
>
> — <cite>Hervy Qurrotul A.</cite>

## Contact

Email is the best way to reach me. I occasionally use social platforms
such as Mastodon, Bluesky, and Lemmy, but for direct communication I
prefer SimpleX Chat or Signal.

- Email: [hervyqa@disroot.org](https://hervyqa.site/link/email)
- Direct Message: {{ go(id="sxc") }} or {{ go(id="sgnl") }}
- Mastodon: [datasci.social/@hervyqa](https://hervyqa.site/link/mstd)
- Bluesky: [hervyqa.bsky.social](https://hervyqa.site/link/bsky)
- Lemmy: [hervyqa@lemmy.org](https://hervyqa.site/link/lemmy)

> [!WARNING]
> I no longer use Google services, WhatsApp, Facebook, Instagram,
> LinkedIn, Reddit, or Matrix due to concerns regarding privacy, data
> ownership, and platform policies.

## Encrypted Email

I strongly encourage the use of OpenPGP (GPG) for email communication.
Unencrypted email offers little privacy, while encryption helps ensure
that messages can only be read by their intended recipients.

You can find my public key and instructions for importing and verifying
it below.

- Key file: [hervyqa.key](https://hervyqa.srht.site/hervyqa.key).
- Key ID: `0xD7B52C04D9B40738`.
- Fingerprint: `5A13 1FCD DAC2 8768 02F6 31D1 D7B5 2C04 D9B4 0738`.

<details>
<summary>How to import key and verify.</summary>

Import the key from a keyserver:

```bash
gpg --recv-keys D7B52C04D9B40738
```

Or download and import manually:

```bash
wget https://hervyqa.srht.site/hervyqa.key
gpg --import hervyqa.key
```

You can verify the fingerprint after import with:

```bash
gpg --fingerprint D7B52C04D9B40738
```
</details>

## Repository

Most of my open-source work is hosted on SourceHut. While I still
maintain accounts on other platforms, SourceHut is currently my
preferred git forge.

- Sourcehut: [https://git.sr.ht/~hervyqa](https://git.sr.ht/~hervyqa)

## Desktop setup

My workflow is heavily keyboard-driven and centered around CLI and TUI
applications. While my [obsdc] dotfiles setup may not be
the most practical solution for every use case, it is the environment I
enjoy working in.

My daily tools include OpenBSD, SwayWM, Git, Aerc, Vim, Helix, Chawan,
and various CLI/TUI utilities.

[obsd]: https://wwww.openbsd.org
[obsdc]: https://git.sr.ht/~hervyqa/obsdc
