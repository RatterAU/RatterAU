<img src="https://raw.githubusercontent.com/RatterAU/RatterAU/main/docs/profile-banner.svg" width="480" alt="RatterAU — I build apps for things I want a better version of">

If the app doesn't exist, I make it. If it exists but does half of what I need, I make that too.

Australian. Swift, mostly. Everything here runs on the device, talks straight to the source, and keeps no account of you.

<br>

<table>
<tr>
<td width="200" valign="top">
<a href="https://github.com/RatterAU/AdelaideTransit"><img src="https://raw.githubusercontent.com/RatterAU/AdelaideTransit/main/docs/demo.gif" width="190" alt="Adelaide Transit demo"></a>
</td>
<td valign="top">

### [Adelaide Transit](https://github.com/RatterAU/AdelaideTransit)

Live tracking for every Adelaide Metro bus, tram and train.

The official app tells you when a bus is *scheduled*. Standing at a stop in the rain, that's the wrong number — so I built the one that shows where the bus actually is, how late it actually is, and whether I can still make it on foot.

Tap a stop, see what's really coming. Tap a departure, follow the bus itself: its speed, how many seconds ago it reported, every stop still ahead of it.

No accounts, no backend, no analytics. SwiftUI, on-device SQLite, straight off the public GTFS feeds.

[How to install](https://github.com/RatterAU/AdelaideTransit#install-it) · iPhone app, no App Store listing. You build it yourself in Xcode: free, about ten minutes.

`Swift 6` · `SwiftUI` · `MapKit` · `SQLite` · `GTFS-realtime`

</td>
</tr>
<tr>
<td width="200" valign="top">
<a href="https://github.com/RatterAU/tenfold"><img src="https://raw.githubusercontent.com/RatterAU/tenfold/main/docs/chain.png" width="190" alt="TENFOLD strike ladder"></a>
</td>
<td valign="top">

### [TENFOLD](https://github.com/RatterAU/tenfold)

Every SPX strike, in SPY terms — for 0DTE.

SPY is not SPX ÷ 10. The ratio drifts, and on 0DTE that drift is a whole strike, so the mirror runs off the live ratio instead of the shortcut everyone quotes.

Quote tiles, the live ratio, a depth picker and the strike ladder with the spot band. Opens in the browser: no install, no signup, no key.

[Try it here](https://ratterau.github.io/tenfold/) · one HTML file, no dependencies, no build step, no tracking.

`HTML` · `Vanilla JS` · `0DTE` · `SPX/SPY`

</td>
</tr>
<tr>
<td width="200" valign="top">
<a href="https://github.com/RatterAU/basis"><img src="https://raw.githubusercontent.com/RatterAU/basis/main/docs/card.svg" width="190" alt="BASIS average cost card"></a>
</td>
<td valign="top">

### [BASIS](https://github.com/RatterAU/basis)

What the position actually cost you, and what the next buy does to it.

Ten contracts at $1.00 and one at $2.00 is not a $1.50 average, it is $1.09 — which is the arithmetic people do in their head at the exact moment it matters most.

Fills go in, the weighted average comes out in money rather than points. Model the next buy before committing it, watch the curve flatten toward a price it can never reach, or ask it the inverse: how many at $0.55 to get the average to $0.80.

[Try it here](https://ratterau.github.io/basis/) · one HTML file, no dependencies, no build step, no tracking.

`HTML` · `Vanilla JS` · `Options` · `Cost basis`

</td>
</tr>
<tr>
<td width="200" valign="top">
<a href="https://github.com/RatterAU/Bookie"><img src="https://raw.githubusercontent.com/RatterAU/RatterAU/main/docs/bookie-card.svg" width="190" alt="Bookie price board — win prices in lime, place prices in yellow"></a>
</td>
<td valign="top">

### [Bookie](https://github.com/RatterAU/Bookie)

An on-course bookmaker's satchel, on a Mac.

Fielding a race meeting is a speed problem wearing a maths problem's clothes. The arithmetic is easy. Doing it while a punter is mid-sentence and eleven other people are holding cash is not.

So: stake, runner, one letter, and the docket prints on the keystroke. Price boards for up to four TVs, and settlement that never leaves a punter worse off than the paper in their hand.

[How to install](https://github.com/RatterAU/Bookie#install) · Mac app for macOS 14+. You build it yourself with Apple's free Command Line Tools, no Xcode needed.

`Swift` · `SwiftUI` · `SQLite` · `Combine` · `ESC/POS over USB`

</td>
</tr>
</table>
