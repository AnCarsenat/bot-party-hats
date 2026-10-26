# Hats — a Bot Party mod

Six things for the robots to wear in [Bot Party](https://github.com/AnCarsenat/bot-party):
top hat, party hat, crown, propeller cap, headphones and sunglasses.

## Install

In the game: **Mods → Explore → Hats**. Or download `hats.pck` from the
[latest release](../../releases/latest) and put it in the game's mods folder
(**Mods → Open mods folder**), then switch it on in **Mods**.

Choose who wears what in **Mods → Looks**. Online, the host sends the mod to
players who don't have it.

## Make your own

Each look is a 32x32 picture, listed in `mod.json` under `"cosmetics"`
(`"slot": "face"` moves with the eyes; `"offset"` moves it). See
[MODDING.md](https://github.com/AnCarsenat/bot-party/blob/main/MODDING.md).

Releases are made by GitHub Actions: raise `version` in `mod.json`, then
`git tag v1.1 && git push origin v1.1`.

## License

The pictures are under
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/), like
Bot Party's art: credit "Bot Party by AnCarsenat", no commercial use, share
alike. See [LICENSE.md](LICENSE.md).
