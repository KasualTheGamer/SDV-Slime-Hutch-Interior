# KTG's Slime Hutch Interior

I got bored with the regular slime hutch interior, and going in there feels like a chore to me, so I made this to make the interior more fun. 

This map provides more room in the Slime Hutch, an auto-fenced area where you can corral your slimes, and fishing that matches the town and the mountain area fishing, plus Slime Jacks and Midnight Carp felt appropriate for the fishing.

# Config Options

SMAPI will generate a config file that looks like the below. I suggest using [GMCM]() to allow managing the options in game.

```
{
  "EnableFishing": "true",
  "NoSpoilers": "true"
}
```

`EnableFishing` can take either `true` or `false` values. `True` lets you fish in the stream inside the Slime Hutch. `False` disables fishing in the Slime Hutch. 

`EnableFishing` has to be set to `true` for the `NoSpoilers` option to have any affect. It, likewise, takes either `true` or `false` values, and when `true` limits fishing to just the fish that are can be fished up in the Town or the Mountain map **until** the current player visits the map where Slime Jacks spawn. When `false` and `EnableFishing` is `true`, Slime Jacks can be fished up at all times, and Midnight Carp can be caught even in Spring or Summer, though still only between 10 PM and 2 AM.


# Acknowledgements

A big thanks to bblueberry on the SDV Discord modders chat for help getting the fishing to work!