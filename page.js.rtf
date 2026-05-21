{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 "use client";\
import \{ useState \} from "react";\
\
const WORDS = [\
  \{ word: "Sea", group: "Sounds like a letter" \},\
  \{ word: "Queue", group: "Sounds like a letter" \},\
  \{ word: "You", group: "Sounds like a letter" \},\
  \{ word: "Tea", group: "Sounds like a letter" \},\
\
  \{ word: "Score", group: "___ board" \},\
  \{ word: "Surf", group: "___ board" \},\
  \{ word: "Key", group: "___ board" \},\
  \{ word: "Snow", group: "___ board" \},\
\
  \{ word: "Listen", group: "Anagrams" \},\
  \{ word: "Silent", group: "Anagrams" \},\
  \{ word: "Enlist", group: "Anagrams" \},\
  \{ word: "Tinsel", group: "Anagrams" \},\
\
  \{ word: "Un", group: "Means not" \},\
  \{ word: "Non", group: "Means not" \},\
  \{ word: "In", group: "Means not" \},\
  \{ word: "Im", group: "Means not" \},\
];\
\
function shuffle(arr) \{\
  return [...arr].sort(() => Math.random() - 0.5);\
\}\
\
export default function Page() \{\
  const [tiles, setTiles] = useState(shuffle(WORDS));\
  const [selected, setSelected] = useState([]);\
  const [message, setMessage] = useState("");\
\
  const toggle = (tile) => \{\
    if (selected.includes(tile)) \{\
      setSelected(selected.filter((t) => t !== tile));\
    \} else if (selected.length < 4) \{\
      setSelected([...selected, tile]);\
    \}\
  \};\
\
  const submit = () => \{\
    if (selected.length !== 4) return;\
\
    const group = selected[0].group;\
    const correct = selected.every((t) => t.group === group);\
\
    if (correct) \{\
      setTiles(tiles.filter((t) => !selected.includes(t)));\
      setSelected([]);\
      setMessage("Correct!");\
    \} else \{\
      setSelected([]);\
      setMessage("Try again");\
    \}\
  \};\
\
  return (\
    <div style=\{\{ padding: 20 \}\}>\
      <h1>Connections Game</h1>\
\
      <div style=\{\{ display: "grid", gridTemplateColumns: "repeat(4, 1fr)", gap: 10 \}\}>\
        \{tiles.map((t, i) => (\
          <button key=\{i\} onClick=\{() => toggle(t)\}>\
            \{t.word\}\
          </button>\
        ))\}\
      </div>\
\
      <button onClick=\{submit\}>Submit</button>\
      <p>\{message\}</p>\
    </div>\
  );\
\}}