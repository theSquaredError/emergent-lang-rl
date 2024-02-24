<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emergent Communication properties</title>
    <base target="_blank" rel="noopener noreferrer">
    <style>
        .content {
            width: 70%; /* Could be anything, but 75% works here. */
            margin: auto; /* This is what center the content div itself. */
            /* border: 1px solid red; */
        }
        header h1 {
            font-size: 40px;
            font-weight: 600;
            background-image: linear-gradient(to left, #553c9a, #b393d3);
            color: transparent;
            background-clip: text;
            -webkit-background-clip: text;
            padding: 10px 20px;
            text-align: center;
            margin-bottom: auto;
            position: relative;
            
        }
        body {
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f3f3;
            color: #333;
        }
        /* header {
            background-color: #699ac5;
            color: white;
            padding: 10px 20px;
            text-align: center;
            margin-bottom: auto;
            position: relative;
        } */
        nav {
            background-color: #1565c0;
            padding: 10px 20px;
            text-align: center;
            display: none; /* Hide the navigation initially on small screens */
        }
        nav a {
            color: white;
            text-decoration: none;
            margin-right: 20px;
        }
        main {
            padding: 20px;
            /* justify-content: center; */
            text-align: center;
        }
        article {
            background-color: #fff;
            border-radius: 5px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        footer {
            /* background-color: #1e88e5; */
            color: black;
            text-align: center;
            padding: 10px 20px;
            /* position: fixed; */
            bottom: 0;
            width: 100%;
        }
        table{
            border-radius: 1px;
            text-align: center;
            justify-content: center;
        }

        td, th {
            border: 1px solid #dddddd;
            text-align: left;
            padding: 8px;
        }
        p{
            text-align: justify;
            font-size: large;
        }
        /* Responsive styles */
        @media only screen and (min-width: 768px) {
            nav {
                display: block; /* Display the navigation for larger screens */
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>Emergent Language properties in Multi-Agent Communication</h1>
    </header>
    <main class="content">
    
            <h2>Can robots exhibit sufficient creativity to autonomously invent their own language?</h2>
            <p>My current research endeavors to tackle a fundamental question: ”Can robots exhibit sufficient creativity 
                to autonomously invent their own language?” 
                The ability to communicate ideas using oral symbols is a remarkably complex yet highly effective mechanism 
                developed and mastered by humans. This skill, rooted in well-structured languages grounded within societal 
                contexts, presents a fundamental challenge for artificial intelligence.</p>
            <p>If we aim to achieve the formation of communication from first principles, it must arise out of necessity. 
                Existing approaches that learn to imitate language from examples of human language (such as NLP) may capture 
                statistical patterns but often fall short in understanding the underlying reasons for language’s 
                existence and fail to encompass its functional aspects.</p>
            <p>In my research, I employ deep reinforcement learning techniques within the framework of multi-agent markov games. 
                The primary objective is to construct computational models that shed light on the processes underlying the 
                emergence of phenomena like shared lexicons (grounding) and grammars, mirroring aspects of human language evolution.</p>
            
            <p>A lexicon represents a systematic set of associations between linguistic forms and their meanings. 
                However, the emergence of a shared grammar presents a more intricate problem. Grammar encompasses 
                properties of language involving the sequential arrangement of lexical forms, which together form expressions or sentences.</p>
            <br>
            <hr>
            <h2 id="_existing-literature-for-language-emergence_"><u> Existing Literature for language emergence</u></h2>

            <table>
                <thead>
                    <tr>
                    <th>Title</th>
                    <th>Author</th>
                    <th>Venue</th>
                    <th>Year</th>
                    </tr>
                </thead>
            <tbody>
            <tr>
            <td><a href="https://toruowo.github.io/marl-ae-comm/" target="_blank">Learning to Ground Multi-Agent Communication with Autoencoders</a></td>
            <td>d</td>
            <td>NIPS</td>
            <td>2021</td>
            </tr>
            <tr>
            <td><a href="https://arxiv.org/pdf/1703.04908.pdf" target="_blank">Emergence of Grounded compositional langauage in multi agent population</a></td>
            <td>d</td>
            <td>AAAI</td>
            <td>d</td>
            </tr>
            <tr>
            <td><a href="https://aclanthology.org/D17-1321.pdf">Natural Language Does Not Emerge ‘Naturally’ in Multi-Agent Dialog</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>
            <tr>
            <td><a href="https://openreview.net/pdf?id=HJGv1Z-AW">EMERGENCE OF LINGUISTIC COMMUNICATION FROM REFERENTIAL GAMES WITH SYMBOLIC AND PIXEL</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>
            <tr>
            <td><a href="https://proceedings.neurips.cc/paper/2016/file/55b1927fdafef39c48e5b73b5d61ea60-Paper.pdf">Learning Multiagent Communication with Backpropagation</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>
            <tr>
            <td><a href="https://digital.csic.es/bitstream/10261/128155/1/Evolving%20grounded.pdf">Evolving Grounded Communication for robots</a></td>
            <td>Luc Steels</td>
            </tr>
            <tr>
            <td><a href="https://openaccess.thecvf.com/content_ICCV_2017/papers/Das_Learning_Cooperative_Visual_ICCV_2017_paper.pdf">Learning Cooperative visual dialog agents with deep reinforcement learning</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>
            <tr>
            <td><a href="https://arxiv.org/pdf/1705.11192.pdf">Emergence of Language with Multi-agent Games: Learning to Communicate with Sequences of Symbols</a></td>
            <td>Angeliki Lazaridou</td>
            <td>d</td>
            <td>d</td>
            </tr>
            <tr>
            <td><a href="http://www.openreview.net/pdf?id=HkePNpVKPB">Compositional languages emerge in a neural iterated learning model</a></td>
            <td>Yi Ren, Simon Kirby</td>
            <td>d</td>
            <td>d</td>
            </tr>
            <tr>
            <td><a href="https://arxiv.org/pdf/1710.06922.pdf">EMERGENT TRANSLATION IN MULTI-AGENT COMMUNICATION</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>
            
            <tr>
            <td><a href="https://arxiv.org/pdf/2004.02780.pdf">Networked Multi-Agent Reinforcement Learning with Emergent Communication</a></td>
            <td>Shubham Gupta</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://yzhu.io/courses/core/reading/06.tomasello.pdf">Origins of Human Communication</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://arxiv.org/pdf/1910.05291.pdf">The Emergence of Compositional Languages for Numeric Concepts Through Iterated Learning in Neural Agents</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="http://www.lel.ed.ac.uk/~simon/Papers/Kirby/thesis.pdf">Function, Selection and Innateness The Emergence of Language Universals</a></td>
            <td>Simon Kirby</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://proceedings.neurips.cc/paper_files/paper/2019/file/fe5e7cb609bdbe6d62449d61849c38b0-Paper.pdf">Biases for Emergent Communication in Multi-agent Reinforcement Learning</a></td>
            <td>Simon Kirby</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://openreview.net/pdf?id=AUGBfDIV9rL">EMERGENT COMMUNICATION AT SCALE</a></td>
            <td>Rahma Chaabouni, Angeliki Lazaridou</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://aclanthology.org/2020.acl-main.407.pdf">Compositonality and Generalization in Emergent Languages</a></td>
            <td>Rahma Chaabouni, Marco Baroni</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://www.researchgate.net/profile/Robin-Campbell/publication/265778931_The_Study_of_Language_Acquisition/links/5695a83908ae425c68985e25/The-Study-of-Language-Acquisition.pdf">THE STUDY OF LANGUAGE ACQUISITION</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://aclanthology.org/D18-1119.pdf">How agents see things: On visual representations in an emergent language game</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://openreview.net/pdf?id=HJz05o0qK7">Measuring Compositionality in representation learning</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://sites.socsci.uci.edu/~lpearl/courses/readings/PerforsEtAl2010_RecursiveLang.pdf">How recursive is language? A Bayesian exploration</a>)</td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://www.science.org/doi/pdf/10.1126/science.298.5598.1569">The Faculty of Language: What Is It, Who Has It, and How Did It Evolve?</a></td>
            <td>d</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://citeseerx.ist.psu.edu/document?repid=rep1&amp;type=pdf&amp;doi=6a54db36afce548b5e4deefb3a4df0428a13a813">Understanding Linguistic Evolution by Visualizing the Emergenceof Topographic Mappings</a></td>
            <td>Simon Kirby</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://hal.science/hal-02274205/document#:~:text=Surprisingly%2C%20we%20find%20that%20networks,towards%20the%20maximum%20length%20threshold." target="_blank">Anti-Efficient encoding in the emergent language</a></td>
            <td>Chaabouni</td>
            <td>d</td>
            <td>d</td>
            </tr>

            <tr>
            <td><a href="https://proceedings.neurips.cc/paper/2016/file/c7635bfd99248a2cdef8249ef7bfbef4-Paper.pdf">Learning to Communicate with Deep Multi-Agent Reinforcement Learning</a></td>
            <td>Jakob N. Foerster,Shimon Whiteson</td>
            <td>NIPS</td>
            <td>2016</td>
            </tr>

            <tr>
                <td><a href="https://arxiv.org/pdf/2112.14518.pdf">MUTUAL INFLUENCE BETWEEN LANGUAGE AND PERCEPTION IN MULTI-AGENT COMMUNICATION GAMES</a></td>
                <td>Xenia Ohmer</td>
                <td>PLOS</td>
                <td>2022</td>
            </tr>

            <tr>
                <td><a href="http://www.lel.ed.ac.uk/~simon/Papers/Kirby/The%2520Evolution%2520of%2520Language.pdf">The Evolution of Language</a></td>
                <td>Simon Kirby</td>
                <td></td>
                <td>2007</td>
            </tr>
            </tbody>
            </table>
</main>
    <footer>
        &copy; 2024 Vikas Kumar
    </footer>
</body>
</html>
