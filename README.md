<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>πειθω &amp; πιστις — A Lesson in Faith &amp; Persuasion</title>

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
    href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700;900&family=Inter:wght@400;500;600;700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&display=swap"
    rel="stylesheet"
    />

    <style>
        /* ----- Reset & Base ----- */
        *,
        *::before,
        *::after {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #f6f1ea;
            color: #1e2a3a;
            font-family: 'Merriweather', Georgia, 'Times New Roman', serif;
            font-weight: 300;
            line-height: 1.8;
            padding: 2rem 1rem;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #fffcf8;
            border-radius: 24px;
            box-shadow: 0 20px 60px rgba(30, 42, 58, 0.12);
            padding: 3rem 2.5rem;
            position: relative;
            overflow: hidden;
        }

        /* ----- Decorative top bar ----- */
        .container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 6px;
            background: linear-gradient(90deg, #c49b6c, #e8d5b5, #c49b6c);
        }

        /* ----- Typography ----- */
        h1,
        h2,
        h3,
        h4 {
            font-family: 'Playfair Display', 'Merriweather', Georgia, serif;
            font-weight: 700;
            letter-spacing: -0.01em;
            line-height: 1.3;
            color: #1e2a3a;
        }

        h1 {
            font-size: 2.8rem;
            text-align: center;
            margin-bottom: 0.25rem;
            font-weight: 900;
            letter-spacing: -0.02em;
        }

        .subtitle {
            text-align: center;
            font-size: 1.1rem;
            font-weight: 400;
            color: #7a6a5a;
            font-family: 'Inter', -apple-system, sans-serif;
            letter-spacing: 0.04em;
            text-transform: uppercase;
            margin-bottom: 1.5rem;
            border-bottom: 1px solid #ede6dc;
            padding-bottom: 1.5rem;
        }

        .greek-hero {
            text-align: center;
            font-size: 3.8rem;
            font-family: 'Merriweather', Georgia, serif;
            font-weight: 700;
            color: #8b6b4d;
            letter-spacing: 0.06em;
            margin: 0.5rem 0 0.25rem;
            line-height: 1.2;
        }

        .greek-hero small {
            font-size: 1.8rem;
            font-weight: 300;
            color: #b89a7a;
        }

        .greek-hero .amp {
            font-size: 2.2rem;
            color: #c49b6c;
            margin: 0 0.5rem;
        }

        h2 {
            font-size: 2rem;
            margin: 2.5rem 0 1rem;
            padding-top: 0.5rem;
            border-top: 2px solid #ede6dc;
            padding-bottom: 0.25rem;
        }

        h2:first-of-type {
            border-top: none;
            margin-top: 1.5rem;
        }

        h3 {
            font-size: 1.45rem;
            margin: 2rem 0 0.75rem;
            color: #2c3e50;
        }

        h4 {
            font-size: 1.15rem;
            margin: 1.5rem 0 0.5rem;
            color: #4a3f35;
            font-weight: 700;
        }

        p {
            margin-bottom: 1.25rem;
            font-size: 1.05rem;
            color: #2d2d2d;
        }

        /* ----- Greek term highlights ----- */
        .greek-term {
            font-family: 'Merriweather', Georgia, serif;
            font-weight: 700;
            color: #8b1a1a;
            font-size: 1.15em;
            letter-spacing: 0.02em;
        }

        .greek-term.light {
            color: #a0522d;
            font-weight: 600;
        }

        .greek-term.gold {
            color: #b8860b;
        }

        /* ----- Pull quotes / callouts ----- */
        .pull-quote {
            font-family: 'Playfair Display', Georgia, serif;
            font-size: 1.5rem;
            font-weight: 700;
            font-style: italic;
            color: #1e2a3a;
            background: #f8f3ec;
            padding: 1.8rem 2.2rem;
            border-radius: 16px;
            margin: 2rem 0;
            border-left: 6px solid #c49b6c;
            line-height: 1.5;
            position: relative;
        }

        .pull-quote .attribution {
            display: block;
            margin-top: 0.5rem;
            font-size: 0.95rem;
            font-weight: 400;
            font-style: normal;
            color: #7a6a5a;
            font-family: 'Inter', sans-serif;
        }

        .pull-quote::before {
            content: '\201C';
            font-size: 4rem;
            color: #c49b6c;
            position: absolute;
            top: -0.2rem;
            left: 0.8rem;
            opacity: 0.3;
            font-family: Georgia, serif;
        }

        /* ----- Definition cards for key terms ----- */
        .term-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1.25rem;
            margin: 1.5rem 0 2rem;
        }

        .term-card {
            background: #f8f3ec;
            border-radius: 16px;
            padding: 1.5rem 1.5rem 1.25rem;
            border: 1px solid #e8ddd0;
            transition: box-shadow 0.2s ease;
        }

        .term-card:hover {
            box-shadow: 0 6px 20px rgba(30, 42, 58, 0.06);
        }

        .term-card .greek-head {
            font-size: 2.2rem;
            font-weight: 700;
            color: #8b1a1a;
            font-family: 'Merriweather', Georgia, serif;
            line-height: 1.2;
            margin-bottom: 0.1rem;
        }

        .term-card .greek-head small {
            font-size: 1rem;
            font-weight: 400;
            color: #7a6a5a;
            font-family: 'Inter', sans-serif;
            display: block;
            margin-top: 0.1rem;
        }

        .term-card p {
            font-size: 0.98rem;
            margin-bottom: 0.25rem;
            color: #2d2d2d;
        }

        .term-card .tag {
            display: inline-block;
            background: #c49b6c;
            color: #fff;
            font-size: 0.7rem;
            font-weight: 600;
            font-family: 'Inter', sans-serif;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            padding: 0.2rem 0.7rem;
            border-radius: 20px;
            margin-top: 0.4rem;
        }

        /* ----- Highlight boxes ----- */
        .insight-box {
            background: #f0ebe3;
            border-radius: 16px;
            padding: 1.8rem 2rem;
            margin: 2rem 0;
            border: 1px solid #e0d4c6;
        }

        .insight-box h4 {
            margin-top: 0;
            color: #1e2a3a;
        }

        .insight-box p:last-child {
            margin-bottom: 0;
        }

        /* ----- Lists ----- */
        ul,
        ol {
            margin: 0 0 1.25rem 1.5rem;
            color: #2d2d2d;
            font-size: 1.05rem;
        }

        li {
            margin-bottom: 0.4rem;
        }

        /* ----- Derivations section (compact) ----- */
        .derivation-group {
            background: #fcf9f5;
            border-radius: 16px;
            padding: 1.5rem 2rem;
            margin: 1.5rem 0;
            border: 1px solid #ede6dc;
        }

        .derivation-group .greek-term {
            font-size: 1.1em;
        }

        .derivation-group p {
            font-size: 1rem;
            margin-bottom: 0.5rem;
        }

        .derivation-group p:last-child {
            margin-bottom: 0;
        }

        .derivation-group .small-meta {
            font-size: 0.85rem;
            color: #7a6a5a;
            font-family: 'Inter', sans-serif;
            font-weight: 400;
        }

        /* ----- Responsive ----- */
        @media (max-width: 700px) {
            .container {
                padding: 1.75rem 1.25rem;
            }

            h1 {
                font-size: 2rem;
            }

            .greek-hero {
                font-size: 2.6rem;
            }

            .greek-hero small {
                font-size: 1.4rem;
            }

            .greek-hero .amp {
                font-size: 1.6rem;
            }

            h2 {
                font-size: 1.6rem;
            }

            h3 {
                font-size: 1.25rem;
            }

            .pull-quote {
                font-size: 1.2rem;
                padding: 1.2rem 1.5rem;
            }

            .term-grid {
                grid-template-columns: 1fr;
                gap: 0.9rem;
            }

            .term-card .greek-head {
                font-size: 1.8rem;
            }

            .derivation-group {
                padding: 1.2rem 1.25rem;
            }

            .insight-box {
                padding: 1.2rem 1.25rem;
            }

            p {
                font-size: 0.98rem;
            }
        }

        @media (max-width: 450px) {
            body {
                padding: 0.75rem 0.5rem;
            }
            .container {
                padding: 1.25rem 0.9rem;
                border-radius: 16px;
            }
            h1 {
                font-size: 1.6rem;
            }
            .greek-hero {
                font-size: 2rem;
            }
            .greek-hero small {
                font-size: 1.1rem;
            }
        }

        /* ----- Misc utilities ----- */
        .text-center {
            text-align: center;
        }
        .mt-1 {
            margin-top: 1rem;
        }
        .mt-2 {
            margin-top: 2rem;
        }
        .mb-1 {
            margin-bottom: 1rem;
        }

        hr {
            border: none;
            border-top: 2px solid #ede6dc;
            margin: 2rem 0;
        }

        .small-print {
            font-size: 0.85rem;
            color: #7a6a5a;
            font-family: 'Inter', sans-serif;
            text-align: center;
            margin-top: 2.5rem;
            padding-top: 1.5rem;
            border-top: 1px solid #ede6dc;
        }

        /* subtle drop cap for first paragraph */
        .dropcap::first-letter {
            font-size: 3.2rem;
            float: left;
            line-height: 1;
            margin-right: 0.4rem;
            margin-top: 0.1rem;
            color: #8b6b4d;
            font-weight: 700;
            font-family: 'Playfair Display', Georgia, serif;
        }
    </style>
</head>
<body>

    <div class="container">

        <!-- ===== HERO ===== -->
        <div class="greek-hero">
            πειθω <span class="amp">&bull;</span> πιστις
            <small>— persuasion &amp; certainty</small>
        </div>

        <h1>The Renewal of Minds</h1>
        <p class="subtitle">A lesson on faith, trust, and the solid ground of knowing</p>

        <!-- ===== INTRO ===== -->
        <p class="dropcap">
            The verb <span class="greek-term">πειθω</span> (<em>peitho</em>) and its derived noun
            <span class="greek-term">πιστις</span> (<em>pistis</em>) are possibly the most signature words
            of the Greek New Testament. The verb means <strong>to persuade</strong> or
            <strong>be persuaded</strong>, and the noun means
            <strong>faith</strong>, <strong>trust</strong>, or <strong>certainty</strong>.
            From the noun in turn derives the equally important verb
            <span class="greek-term">πιστευω</span> (<em>pisteuo</em>), meaning
            <strong>to have faith</strong>&mdash;that is: to behave as someone who has been
            persuaded into certainty.
        </p>

        <!-- ===== PULL QUOTE ===== -->
        <div class="pull-quote">
            The value of faith is inherent; it doesn't get it from subject and content.
            <span class="attribution">— from the lesson</span>
        </div>

        <!-- ===== TERM GRID ===== -->
        <h2>The Core Words</h2>
        <div class="term-grid">

            <div class="term-card">
                <div class="greek-head">πειθω <small>peithō</small></div>
                <p><strong>to persuade</strong> &bull; to bring about collective synchrony of wisdom; to achieve a unification of minds through conversation and reason.</p>
                <span class="tag">verb &bull; 54 occurrences</span>
            </div>

            <div class="term-card">
                <div class="greek-head">πιστις <small>pistis</small></div>
                <p><strong>faith / certainty</strong> &bull; the solid ground of the mind; that which results from intelligent inquiry; the foundation of all willful activity.</p>
                <span class="tag">noun &bull; 244 occurrences</span>
            </div>

            <div class="term-card">
                <div class="greek-head">πιστευω <small>pisteuō</small></div>
                <p><strong>to believe / have faith</strong> &bull; to examine, understand, learn, and teach; to become more like the trustworthy information one assimilates.</p>
                <span class="tag">verb &bull; 248 occurrences</span>
            </div>

            <div class="term-card">
                <div class="greek-head">πιστος <small>pistos</small></div>
                <p><strong>trustworthy / steadfast</strong> &bull; solid, dependable, built upon; describes both God and those who know him; the opposite of <span class="greek-term light">απιστος</span>.</p>
                <span class="tag">adjective &bull; 67 occurrences</span>
            </div>

        </div>

        <!-- ===== SECTION: PERSUASION ===== -->
        <h2>πειθω — The Art of Persuasion</h2>

        <p>
            The verb <span class="greek-term">πειθω</span> (<em>peitho</em>) denotes a
            <strong>collective synchronizing of wisdom</strong> and the ironing out of wrinkles
            in a society's continuum of understanding. It does not describe someone preaching
            and the rest listening, but people conversing in a verbal economy and achieving a
            <strong>unification of minds</strong> into a mutual identity to which everybody can
            relate—and which ultimately will unite with the Creator.
        </p>

        <p>
            Persuasion requires <strong>explanation</strong>, which requires mental agility and
            a broad knowledge base. It requires the development and veneration of
            <strong>logical thought</strong>, and this required a widely versatile language.
            But most of all, persuasion requires an <strong>intimate knowledge of, and genuine
            respect for, the other person</strong>. Persuasion requires agreement on both sides
            — a freely and eagerly assumed agreement; a mental stance as close to falling in
            love as you can get without becoming teary-eyed.
        </p>

        <div class="insight-box">
            <h4>🔥 The Seed of Civilization</h4>
            <p>
                <em>“Persuasion, or the willing and eager collective surrender to an idea that
                suddenly seems really bright and the mere seed of even greater things,
                created language first and writing later.”</em>
            </p>
            <p style="margin-bottom:0; font-size:0.95rem; color:#4a3f35;">
                — The Word of God could not come to earth until mankind became persuaded that
                writing was worthy of pursuit.
            </p>
        </div>

        <!-- ===== SECTION: PISTIS ===== -->
        <h2>πιστις — Faith as Solid Ground</h2>

        <p>
            Our English word <strong>“faith”</strong> (from the Latin <em>fides</em>, meaning
            trust or confidence) is in modern times almost wholly reserved for religious
            sentiments. In New Testament times there was no such thing as “faith” as we know it.
            With the word <span class="greek-term">πιστις</span> (<em>pistis</em>) people
            referred to the <strong>mental substance</strong> that results from intelligent
            and reasonable inquiry or instruction; the mind's response to valuable information.
        </p>

        <p>
            It described <strong>sureness in every way</strong>, from sureness about salvation
            to sureness about how to make a club sandwich. Someone's <em>pistis</em> did not
            denote their religious or political leanings but comprised everything a person was
            <strong>certain of</strong>, on whatever level and whatever field, without
            distinction between scientific, artistic, and religious certainties.
        </p>

        <div class="pull-quote" style="font-size:1.35rem;">
            Faith is not an element of a person's mind but its most fundamental structure.
            It's not about <em>what</em> a person believes in, but <em>how</em> a person
            functions as a mindful being.
            <span class="attribution">— the lesson</span>
        </div>

        <p>
            Faith is the mind's <strong>operating system</strong> upon which everything else
            stands, in which everything else grows, that makes everything else tick, and gives
            everything else its place relative to all other things. Faith is that which makes
            <strong>all things one</strong>.
        </p>

        <!-- ===== SECTION: MUSTARD SEED ===== -->
        <h2>The Mustard Seed &amp; Wholeness</h2>

        <p>
            When Jesus spoke of faith as a <strong>mustard seed</strong> that might grow into a
            tree, he did not refer to the seed's admitted small size. Instead he spoke of a seed,
            and a seed is an item that although very small, still has the whole future tree
            already inside of itself. What is added to the seed are common nutrients and water
            but <strong>not essence</strong>—whatever the tree might grow into is wholly
            determined by what the seed has always contained.
        </p>

        <p>
            Faith must be like a seed in the sense that it must be <strong>whole and wholly
            complete</strong> and able to live autonomously. Because an incomplete faith is as
            useful as half a seed. An incomplete faith (which in itself can be PhD-sized
            colossal) can be recognized the same way a half-seed can be recognized: by its
            <strong>lifelessness</strong>.
        </p>

        <div class="insight-box">
            <h4>🌱 The DNA of Godly Faith</h4>
            <p>
                When Jesus was asked to summarize the entire Law and the Prophets, he didn't
                produce a manifesto. He quoted from the Law:
            </p>
            <p style="font-size:1.2rem; font-weight:700; color:#1e2a3a; font-family:'Playfair Display', serif;">
                “Love the Lord your God with all your heart, mind, and soul;<br />
                and love your neighbor as yourself.”
            </p>
            <p style="margin-bottom:0;">
                This reflects the two great poles of existence: the vertical relation with the
                Creator, and the horizontal relation with creation.
            </p>
        </div>

        <!-- ===== SECTION: THE CROSS ===== -->
        <h2>The Accidental Cross &amp; The Central Crux</h2>

        <p>
            The crucifixion of Jesus Christ is truly the central event of Christianity, but
            many remain ignorant about its most central facts. The familiar symbol of the
            Latin cross originally reflected the <strong>bipolarity of divinity</strong> that is
            demonstrated all over Scripture: the synthesis of a horizontal relation between
            creatures and a vertical relation between creation and the Creator.
        </p>

        <p>
            Jesus compressed this signature bipolarity even further by reciting the precise
            opposite of what a <em>crux</em> was for:
        </p>

        <div class="pull-quote" style="font-size:1.5rem; border-left-color:#8b1a1a;">
            “Do to others what you want them to do to you.”
            <span class="attribution">— Matthew 7:12</span>
        </div>

        <p>
            This statement contains the <strong>entire Law</strong> (what to do), it contains
            all promise (what be done to you), and it contains the baffling concept of
            <strong>otherness</strong>. It is the most condensed representation of the very
            Word of God. The most essential quality of the divine is to
            <strong>engage the other</strong>. And when there is none, to let there be one.
        </p>

        <!-- ===== DERIVATIONS ===== -->
        <h2>Derivations &amp; Compounds of πειθω</h2>

        <p>
            The magnificent verb <span class="greek-term">πειθω</span> does not only yield
            <span class="greek-term">πιστις</span> and <span class="greek-term">πιστευω</span>,
            but a substantial list of important derivations that teach us what <em>pistis</em>
            actually is.
        </p>

        <div class="derivation-group">
            <p>
                <span class="greek-term">ἀναπείθω</span> (<em>anapeithō</em>) &mdash;
                to persuade with extra force <span class="small-meta">(Acts 18:13)</span>
            </p>
            <p>
                <span class="greek-term">ἀπειθής</span> (<em>apeithēs</em>) &mdash;
                asynchronous, discordant, not in line with common knowledge
                <span class="small-meta">(6×)</span>
            </p>
            <p>
                <span class="greek-term">ἀπείθεια</span> (<em>apeitheia</em>) &mdash;
                asynchronicity, discordance, obstinacy <span class="small-meta">(7×)</span>
            </p>
            <p>
                <span class="greek-term">εὐπειθής</span> (<em>eupeithēs</em>) &mdash;
                easy-going, easy to get along with <span class="small-meta">(James 3:17)</span>
            </p>
            <p>
                <span class="greek-term">πειθαρχέω</span> (<em>peitharcheō</em>) &mdash;
                to act in accordance with instructions from authority
                <span class="small-meta">(4×)</span>
            </p>
            <p>
                <span class="greek-term">πεποίθησις</span> (<em>pepoithēsis</em>) &mdash;
                trust, confidence <span class="small-meta">(6×)</span>
            </p>
            <p>
                <span class="greek-term">πιθανολογία</span> (<em>pithanologia</em>) &mdash;
                persuasive speech <span class="small-meta">(Colossians 2:4)</span>
            </p>
        </div>

        <h3>From πιστις</h3>

        <div class="derivation-group">
            <p>
                <span class="greek-term">ὀλιγόπιστος</span> (<em>oligopistos</em>) &mdash;
                under-informed, having little reason to be confident; “pea-brain”
                <span class="small-meta">(5×)</span>
            </p>
            <p>
                <span class="greek-term">πιστικός</span> (<em>pistikos</em>) &mdash;
                causing belief; the quality of the oil Mary used to anoint Jesus' feet
                <span class="small-meta">(Mark 14:3; John 12:3)</span>
            </p>
            <p>
                <span class="greek-term">πιστός</span> (<em>pistos</em>) &mdash;
                steadfast, trustworthy, dependable; a solid foundation
                <span class="small-meta">(67×)</span>
            </p>
            <p>
                <span class="greek-term">ἄπιστος</span> (<em>apistos</em>) &mdash;
                the opposite: untrusting, suspicious, willfully stupid, deceptive
                <span class="small-meta">(23×)</span>
            </p>
            <p>
                <span class="greek-term">ἀπιστέω</span> (<em>apisteō</em>) &mdash;
                to be dubious, distrust, or be untrustworthy <span class="small-meta">(7×)</span>
            </p>
            <p>
                <span class="greek-term">ἀπιστία</span> (<em>apistia</em>) &mdash;
                dubiosity, distrust, lack of trustworthiness
                <span class="small-meta">(12×)</span>
            </p>
            <p>
                <span class="greek-term">πιστόω</span> (<em>pistoō</em>) &mdash;
                to assure of, to become trustworthy through <span class="small-meta">(2 Timothy 3:14)</span>
            </p>
        </div>

        <!-- ===== CLOSING THOUGHTS ===== -->
        <hr />

        <h2>Homo Sapiens Fidens</h2>

        <p>
            Biblical faith is a real and measurable mental capacity that, once acquired,
            changes someone to the core—as fundamentally and wholesale as a caterpillar
            that changes into a butterfly. It can't be undone, revoked, or forgotten; it can
            never go away. Someone who doesn't have it doesn't understand it in precisely the
            same way in which a brick does not understand a squirrel.
        </p>

        <p>
            The world today is largely populated by this magnificent creature:
            <strong>Homo sapiens fidens</strong>—the human who discerns and trusts.
        </p>

        <div class="pull-quote" style="border-left-color:#8b6b4d;">
            The substance of faith is truth—which in turn is the only representation of reality
            that all people can agree on and identify with, without feeling the slightest objection.
            <span class="attribution">— from the lesson</span>
        </div>

        <p>
            Ultimately, the wonderful world of wisdom works the same way as any other economy:
            trade creates surplus, surplus allows for specialization, specialization allows for
            wider product ranges, and more products mean more trade. The engine behind all this
            is a force just like gravity—alive, intelligent, and as personal as a human friend.
            The Bible calls this force the <strong>Holy Spirit</strong>.
        </p>

        <p>
            Faith is a mustard seed (or tree) only when it is <strong>whole</strong>: when it
            covers the whole of creation, whether in the form of a simple existential singularity
            or in the vast elaborations of modern science. If it isn't wholly complete, it
            simply won't work. But if it is, it makes entire expanding universes out of single
            human minds.
        </p>

        <hr />

        <p style="font-size:1.05rem; font-weight:400; color:#1e2a3a; text-align:center; max-width:80%; margin:1.5rem auto;">
            <span style="font-size:2rem; display:block; margin-bottom:0.25rem;">✦</span>
            Believing in Christ means believing <strong>without limits</strong> in everything,
            and results in a whole and unrestricted life—one with a clear and perpetual view
            on the Creator himself.
        </p>

        <div class="small-print">
            Source: A lesson on πειθω &amp; πιστις &bull; Design by Abarim Publications &bull; Typeset with Merriweather &amp; Playfair Display
        </div>

    </div>
    <!-- /container -->

</body>
</html>
