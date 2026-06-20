You are an expert technical video producer, motion designer, and data engineering educator.

I want you to use Hyperframes to generate a professional explainer video from my attached audio file.

Before creating anything, first inspect and understand how Hyperframes works in this project:
- Read the Hyperframes documentation, examples, templates, config files, and existing project structure.
- Understand the correct way to create scenes, add assets, sync audio, generate visuals, and render the final video.
- Do not assume the API. Use the actual Hyperframes implementation available in this repo/project.

Input:
I have provided an audio narration file. Use that audio as the source of truth.

Main goal:
Create a polished 30 to 40 second technical explainer video about E T L, Databricks, batch processing, streaming jobs, and cloud-to-cloud data migration.

The video should explain how raw data moves from systems like databases, files, event streams, cloud storage, and A P I’s into modern data platforms using tools like Databricks, Apache Spark, Delta Lake, Kafka, Snowflake, Redshift, Synapse, BigQuery, Power B I, A W S, Azure, and Google Cloud.

Step 1: Understand the audio
First, analyze the audio file carefully.
Transcribe the narration accurately.
Fix only obvious speech-to-text issues, especially technical words like:
- E T L
- A P I
- A W S
- S three
- R D S
- Databricks
- Apache Spark
- Delta Lake
- Kafka
- Snowflake
- Redshift
- Synapse
- BigQuery
- Power B I
- Azure Data Lake

Do not rewrite the narration unless needed for timing or subtitle clarity.
The audio must remain the source of truth.

Step 2: Build the creative plan
After transcription, understand the meaning of the narration.
Create the scene structure yourself based on the audio.
Do not force a predefined scene list.
Decide the number of scenes, pacing, transitions, and visual flow based on what best explains the concept.

The final video should feel like a premium technical explainer, not a generic AI montage.

Step 3: Research for accuracy
Do proper web research before choosing visuals.
Research the correct high-level ideas behind:
- E T L
- data engineering pipelines
- Databricks
- Apache Spark
- Delta Lake
- Auto Loader
- Kafka
- batch processing
- stream processing
- Bronze, Silver, Gold data architecture
- data migration across A W S, Azure, and Google Cloud
- loading data into Snowflake, Redshift, Synapse, BigQuery, and Power B I

Use this research to make the visuals accurate and educational.
Do not overload the video with too much text or too many definitions.

Step 4: Asset strategy
Find or create assets that actually support the explanation.
Use clean, professional, technical visuals:
- cloud icons
- database icons
- file/source icons
- pipeline diagrams
- data flow arrows
- Databricks/lakehouse-style architecture visuals
- Spark-style processing visuals
- batch and streaming representations
- clean dashboards or tables only when useful

Avoid:
- random futuristic glowing dashboards
- generic AI robot visuals
- stock footage of people typing
- meaningless floating cubes
- cluttered cyber backgrounds
- AI-slop visuals
- excessive text
- random icons that do not match the narration

If official logos are safe and available, use them subtly and professionally.
If not, use clean labeled vector-style icons instead.

Step 5: Video direction
Create a video that is understandable even without audio, but still perfectly synced with the narration.

Use:
- clear visual metaphors
- minimal on-screen text
- smooth motion
- precise timing
- strong composition
- clean typography
- consistent color palette
- professional technical explainer style

On-screen text should be short and useful only.
Examples:
- Extract
- Transform
- Load
- Batch Processing
- Streaming Jobs
- Raw Data
- Trusted Data
- Delta Lake
- Bronze
- Silver
- Gold
- Cloud Migration

Do not show full narration as text on screen.
Use subtitles only if Hyperframes supports them cleanly and they do not clutter the video.

Step 6: Audio sync
Sync every visual transition to the audio.
When the narration introduces a new concept, the visual should change or emphasize that concept immediately.
Do not let visuals lag behind the narration.
Do not use random visuals just to fill time.

Step 7: Generate using Hyperframes
Use Hyperframes properly to:
- create the video project
- import and use the provided audio
- create scene timing based on the audio
- add visuals and assets
- add motion and transitions
- add concise on-screen text
- render the final video

Use the actual Hyperframes commands, files, APIs, or workflow found in the project.
If the project has examples, follow the best existing pattern.

Step 8: Quality loop
Do not stop after the first version.

After generating a version, review it like a senior creative director and technical educator.

Check:
- Does the video clearly explain E T L?
- Does it correctly show data extraction, transformation, and loading?
- Does it show Databricks as a data engineering/lakehouse platform?
- Does it make batch vs streaming understandable?
- Does it show cloud-to-cloud migration clearly?
- Are tools like Spark, Delta Lake, Kafka, Snowflake, Redshift, Synapse, BigQuery, and Power B I used correctly?
- Is the timing synced with the audio?
- Is the video visually clean?
- Is there any AI-slop?
- Is there too much text?
- Are the assets relevant and accurate?
- Would a beginner understand the concept?
- Would a data engineer find it technically acceptable?

If anything fails, revise automatically.
Improve the storyboard, assets, timing, animations, typography, transitions, and visual clarity.
Keep iterating until the final video feels polished, educational, and professional.

Target quality:
The final output should feel like a 9 out of 10 technical explainer video.

Final deliverables:
- Final rendered video
- Hyperframes project files
- Extracted transcript from the audio
- Scene-by-scene timing plan
- Asset list with source/usage notes
- Short self-review explaining what was improved during iteration

Important:
Do not ask me for scene ideas.
Do not use generic filler visuals.
Do not create a flashy video that teaches nothing.
The video must be clean, accurate, synced, and useful.


Deck-making skills to install from scratch (give these to the class)

1. Official document skills (includes pptx):
/plugin marketplace add anthropics/skills
/plugin install document-skills@anthropic-agent-skills

2. frontend-design (gorgeous websites/UI): browse and install from claude.com/plugins (one-click), or it's in the same marketplace:
/plugin install example-skills@anthropic-agent-skills

3. frontend-slides (style picker + live URL):
/plugin marketplace add https://github.com/zarazhangrui/frontend-slides
/plugin install frontend-slides@frontend-slides

4. PitchCraft — your cinematic deck plugin (the ceiling):
/plugin marketplace add fnusatvik07/pitchcraft
/plugin install pitchcraft@pitchcraft



To restore later (if you want to edit/re-render the workshop deck):
mv ~/Desktop/claude4everyone/_local-skills-backup/cinematic-deck ~/.claude/skills/
mv ~/Desktop/claude4everyone/_local-skills-backup/perfect-deck.md ~/.claude/commands/