# Tour Sim v3 Test

Test builds of **Tour Sim v3**, based on v2.2.3. Play: https://jamesgregory5-svg.github.io/tour-sim-v3-test/

## v3.1 (live now): Cart Part Only upgrades
- **Real cart collisions:** carts bump each other, and a hard hit makes a cart spin out before it recovers. This applies to your cart and the CPU carts.
- **Minimap** showing the track, the finish line and every cart.
- **Reverse camera:** hold R or C, or the LOOK BACK button, to see behind you.
- Round spinning wheels, the six difficulty levels and the colored golf ball are all kept from v2.2.3.

## Coming in v3.2: Tournament extras
A live leaderboard while you play, named CPU golfers with their own styles, and a trophy shelf for past tournament wins.

## v3.2
- Live tournament leaderboard during rounds (top 5 + you, thru N; click header to collapse)
- Named CPU golfers with styles: Long hitter, Steady putter, Risk taker, Grinder, Wedge wizard
- Trophy shelf for tournament wins (new save key ts.trophies; old saves load unchanged)

## v3.3: Career (core)
- Menu "Career": create a golfer (name, ball color); save key ts.career, other saves untouched
- 8-event seasons of 18-hole events vs a 39-golfer CPU field (styles, live leaderboard), 4 recurring rivals + 10 tour regulars
- Prize money + ranking points; 1000 points promotes: Regional > Challenger > Pro > Major Series (tougher fields, longer tees)
- Courses unlock by tier (famous ones in Major Series); career screen with rank, earnings, wins, trophies, season history
- Career starts at Reggie difficulty (Hall of Fame level-ups come in v3.5, pro shop in v3.4)

## v3.4: Pro shop
- Career pro shop: drivers, irons, wedges, putters, balls (parody brands, several tiers) and ball trails; prize money only; cart colors stay free
- Accuracy (less miss off aim line), power (carry), consistency (less strike variance) apply to real career shots; small upgrades; stock set = current clubs
- Gear saved in ts.career (old career saves load)
- Career live leaderboard shows the event name; Regional/Reggie field re-tuned so rivals contend (winning score around -2)

## v3.5: Hall of Fame
- Win a Major (Major Series event) or finish No. 1 in the season rankings = Hall of Fame entry + new season one level up (Reggie > Easy > Medium > Hard > PGA > Woods)
- Each level: swing meter ~25-37% faster (career meter .6/.82/1.1/1.42/1.8/2.25x) and CPU fields ~2.5-3 shots per round stronger
- Gear and prize money carry over; back to Regional tier, unlocked courses stay
- Hall of Fame list on the career screen; TOUR SIM CLEARED screen at Woods
- Equipped-gear chip (level, gear, stats for current club) under the live leaderboard in career rounds

## v3.6: Fix and tune pass
- Career swing meter at Woods toned to 2.1x (levels .6/.82/1.1/1.42/1.75/2.1x)
- CPU fields rebalanced by simulation: winning score about -3 (Reggie Regional) up to about -12 (Woods Major); rivals in the top 3 about 80% of events
- Trophy dates use local time
- Live leaderboard sits under the minimap and starts collapsed on small/portrait screens
- Cart Part Only minimap spreads overlapping dots at the start
- Trophy shelf button survives tournament-setup redraws; no duplicate Resume round for career events (Career button resumes); a real tournament in progress is no longer hidden by a career round
- Career ball trail comes only from the pro-shop trail (new career = no trail); regular rounds keep the Customization trail
