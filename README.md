# th.clockwarp~

Create rhythms, subdivisions, probabilities and warping out of a single phasor~

## Support my projects

**Consider to [name a fair price](http://gumroad.com/tmhglnd)**

**or [become a patron](http://patreon.com/timohoogland)**

---

## About

Subdivide or multiply a phasor~ into faster or slower divisions, apply an offset to the clock compared to other clockwarps using the same phasor (or when synced to transport), add a rhythmic pattern with probabilities, add a ratcheting effect with probability and apply a pattern in the ratcheting. Reset the counter every n-division (adjustable). Syncable to the global transport when using a [phasor~ 1n @lock 1]



## Reference

**arguments**
- `subdivision` - divide the phasor with a float or symbol (eg. `1/16`)
- `offset` - offset the clock with a float or symbol (eg. `1/8`)
- `countreset` - reset the note counter after n-division (eg. `1/1`), `0` means no reset and infinite count
- `ratchet` - set the ratchetting probability between 0-1 (default = 0)

**attributes**

**messages**
- `signal` - use incoming phasor to subdivide
- `beatlist` - a list of 1's and 0's representing a rhythmic pattern
- `ratchetlist` - a list of integer multipliers for ratchetting
- `warplist` - upcoming

## Install

```
1. download zip
2. unzip and place in Max Library (on MacOS ~/Documents/Max 8/Library)
3. restart Max8, open a new patcher
```

```
1. open terminal
2. $ cd ~/Documents/Max\ 8/Library
3. $ git clone https://github.com/tmhglnd/th.clockwarp.git
4. restart Max8, open a new patcher
```

# License

MIT License

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.
