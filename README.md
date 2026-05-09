{\rtf1\ansi\ansicpg1252\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Times-Bold;\f1\froman\fcharset0 Times-Roman;\f2\froman\fcharset0 Times-Italic;
}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat0\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 A. The Parsing Layer\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Explain that you use 
\f0\b structured prompting
\f1\b0  to turn a PDF into a JSON object. This allows you to treat a resume as a database rather than just a block of text.\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 B. The Scoring Layer\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Mention that you use 
\f0\b Semantic Similarity
\f1\b0 .\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls1\ilvl0
\f0\b \cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Keyword matching
\f1\b0  is old school.\
\ls1\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Semantic matching
\f1\b0  (what your Gem does) understands that a candidate with "AWS" knowledge is a strong match for a job requiring "Cloud Infrastructure," even if the words don't match exactly.\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 C. The Generation Layer\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Explain that your Gem uses a 
\f0\b Chain-of-Thought (CoT)
\f1\b0  prompt. It doesn't just "rewrite" the resume; it first 
\f2\i analyzes
\f1\i0  what is missing, 
\f2\i plans
\f1\i0  how to fix it, and then 
\f2\i executes
\f1\i0  the rewrite. This prevents the AI from making things up (hallucinations).\
}