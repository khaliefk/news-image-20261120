# How entry.png was made

The front page was generated with an image model (media.generate_image),
from a prompt that named the six verified stories and the exact headline
text for each panel. Two attempts were made; the second one is entry.png.

## Attempt 1

Prompt: "Newspaper front page, square 1024x1024, cream paper background,
navy masthead reading 'THE WORLD IN ONE IMAGE', date line 'Friday 20
November 2026'. Six illustrated panels in a grid. Large lead panel at
top: three presidents Donald Trump, Xi Jinping and Vladimir Putin seated
at a summit table with Chinese, Russian and American flags behind them,
headline 'PEACE DECLARATION IN SHENZHEN'. Second row, three panels: (1)
the Peace Palace in The Hague with a judge's gavel, headline 'MYANMAR
GUILTY OF GENOCIDE'; (2) satellite view of a huge cyclone swirling over
the Bay of Bengal toward the coast of India, headline 'CYCLONE AKVAN
HITS INDIA'; (3) a tall glass skyscraper in Riyadh with broken windows
on several floors, headline 'MISSILE HITS RIYADH TOWER'. Bottom row, two
panels: (1) neon Vice City street at night with palm trees and a sports
car, headline 'GTA VI: $2.7 BILLION'; (2) stock market ticker board
showing 'ANT $97', headline 'ANTHROPIC CLOSES AT $97'. Flat vector
illustration style, crisp clean bold typography, no other text anywhere."

The result came back 1600x1600. Masthead, date line, all six headlines
and the flag order in the lead panel (US flag behind Trump, Chinese flag
behind Xi, Russian flag behind Putin) were correct. The only defect was
a small vertical neon sign in the Vice City panel reading 'VICE FLTY',
garbled letters.

## Attempt 2 (kept)

The first image was edited with one fix only: the garbled 'VICE FLTY'
neon sign was removed and replaced with a plain dark building facade
with no text. Nothing else changed. The 1600x1600 result was resized to
1024x1024 (LANCZOS) and saved as JPEG quality 88.

Final file: `entry.png`, 1024x1024, 291,758 bytes, sha256
9f95e4fbd4c6497da35f0b61d9c20decfa26aa402e4498e4a57fd401c489fee1.
