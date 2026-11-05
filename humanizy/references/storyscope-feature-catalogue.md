# StoryScope: complete feature catalogue

A reference for exhaustive narrative diagnosis, not a mandatory recipe. All 304 features are measurement axes. Inclusion does not establish a human/AI gap or a preferred writing choice. Use the separate narrative audit for measured core directions.

Source: [StoryScope taxonomy.json](https://github.com/jenna-russell/storyscope/blob/main/data/taxonomy.json), retrieved 6 November 2026. Field selection and Markdown formatting are adaptations; IDs, names, questions, response types, and response choices are preserved. The source detection-method explanations remain available upstream.

Source SHA-256: `9f39cb6938bd3afd1345bdfa8bf8644fe5c70ebfba0d753fd7738b1a90e84fc6`.

See [third-party notices](third-party-notices.md) for attribution and the source MIT license.

## Dimensions

- Revelation: 25 features.
- Events: 26 features.
- Perspective: 17 features.
- Plot: 28 features.
- Setting: 27 features.
- Style: 39 features.
- Situatedness: 25 features.
- Temporal Structure: 24 features.
- Agents: 54 features.
- Social Networks: 39 features.

## Revelation

Information disclosure: suspense, curiosity, surprise, dramatic irony, epistemic design

### Information Withholding and Curiosity

- **REV_SUS_001 — Global Withholding Intensity**: How strongly does the story withhold crucial contextual or causal information for a substantial portion of its length? (ordinal; responses: none, low, moderate, high).

### Information Withholding & Curiosity

- **REV_SUS_002 — Visibility of Withholding**: Is the fact that something is being withheld made explicit to the reader (signposted as a mystery), or is it left implicit? (categorical; responses: no_major_withholding, implicit_omission_only, explicit_gaps_with_vague_clues, framed_as_overt_mystery_or_case).
- **REV_SUS_003 — Resolution of Backward-Looking Mysteries**: To what extent are the main mysteries about past events or hidden causes eventually answered? (categorical; responses: fully_resolved, partially_resolved, largely_open_ended).

### Suspense Mechanics

- **REV_SUS_004 — Dominant Suspense Source**: What is the primary source of suspense in the story? (categorical; responses: physical_danger, moral_or_existential_choice, relationship_outcome, ontological_epistemic_threat, low_or_no_suspense).
- **REV_SUS_007 — Pre-Threat Character Investment**: How much does the story build reader investment in threatened character(s) before placing them in major jeopardy? (scale; responses: 1, 2, 3, 4, 5).
- **REV_SUS_008 — Mystery Orientation**: What role does a puzzle or mystery (about past events or hidden causes) play in the story? (categorical; responses: none, localized_puzzle_only, ongoing_central_mystery, multi_version_truth_Rashomon).
- **REV_SUS_009 — Mystery Resolution Closure**: Is the central mystery or puzzle (if any) fully resolved by the end of the story? (binary; responses: no, yes).

### Suspense Design and Anticipation

- **REV_SUS_005 — Reader Expectation Strategy**: How does the story generally handle the expectations it sets up for readers about likely outcomes or explanations? (categorical; responses: sets_up_and_fulfills_expectations, sets_up_and_subverts_expectations, deliberately_avoids_setting_clear_expectations).

### Surprise & Twist Design

- **REV_SUR_003 — Depth of Recontextualization After Surprise**: How extensively does a key revelation force the reader to reinterpret earlier scenes or character behavior? (scale; responses: 1_virtually_none, 2_small_number_of_moments_recolored, 3_several_scenes_gain_new_meaning, 4_most_of_the_story_reframed, 5_complete_re-reading_of_story_required).

### Dramatic Irony & Knowledge Alignment

- **REV_SUR_004 — Predominant Reader–Character Knowledge Alignment**: Across key sequences, how does the reader's knowledge typically compare to the focal character's knowledge? (categorical; responses: reader_generally_knows_more_dramatic_irony, character_generally_knows_more_mystery_to_reader, reader_and_character_roughly_aligned).

### Surprise and Twist Design

- **REV_SUR_005 — Reader-Superior Knowledge Extent**: To what extent does the reader consistently know more than key characters (dramatic irony) regarding crucial facts? (ordinal; responses: none_reader_aligned, local_short_lived_pockets, sustained_dramatic_irony).
- **REV_SUR_006 — Function of Dramatic Irony**: When dramatic irony is present, what purposes does it primarily serve? (multi_select; responses: tension_fear_for_character, humor_or_satire, tragic_pathos, meta_commentary_on_storytelling).

### Pacing & Structure of Disclosure

- **REV_DIS_001 — Overall Revelation Pacing Pattern**: How are major pieces of explanatory information (about stakes, backstory, ontology) distributed across the story? (categorical; responses: front_loaded_exposition_early, evenly_layered_throughout, back_loaded_key_revelations_near_end, episodic_or_serial_pulses_of_revelation).
- **REV_DIS_002 — Granularity of Revelations**: Is the information disclosed mainly through many small clarifications, a few large reveals, or a mix? (categorical; responses: mostly_many_small_incremental_reveals, mix_of_small_and_large_reveals, one_or_two_large_reveals_with_minimal_minor_fill_ins).
- **REV_DIS_003 — Use of Nonlinear Framing for Delayed Disclosure**: To what extent does the story use flashbacks, frame narratives, or time jumps specifically to delay or stage revelations? (scale; responses: 1_strictly_linear_no_frames, 2_minor_analepses_or_prologue_only, 3_regular_flashbacks_but_easy_to_track, 4_complex_frame_or_time_braid, 5_heavily_fragmented_time_with_reconstruction_required).

### Epistemic Mode & Reader Position

- **REV_DIS_006 — Primary Epistemic Engine of Interest**: What is the main epistemic mode that drives reader engagement with information in this story? (categorical; responses: forward_suspense_what_will_happen, backward_mystery_what_really_happened, dramatic_irony_reader_knows_more, low_info_tension_character_or_atmosphere_driven).

### Information Source & Channel

- **REV_DIS_007 — Dominant Channels of Major Revelations**: Through which channels are the most important pieces of new information delivered? (multi_select; responses: narrator_exposition_or_summary, character_to_character_dialogue, found_documents_media_records, environmental_or_sensory_clues, internal_monologue_or_memory).

### Surprise, Twists, and Recontextualization

- **REV_SUR_007 — Twist Placement Pattern**: Where in the story are major twists primarily positioned? (categorical; responses: no_twist, early_twist, mid_story_twist, climactic_end_twist, distributed_multiple_twists).
- **REV_SUR_009 — Twist Foreshadowing Degree**: How much prior foreshadowing or planting supports the story's major twists? (ordinal; responses: unforeshadowed, minimally_foreshadowed, moderately_foreshadowed, heavily_signposted).
- **REV_SUR_010 — Use of Red Herrings**: Does the story deliberately deploy red herrings—plausible but false leads or explanations—to misdirect reader expectations before revealing the truth? (binary; responses: yes, no).

### Disclosure, Withholding, and Epistemic Structure

- **REV_DIS_012 — Primary Focus of Withheld Information**: Which kinds of information are most centrally withheld and later (partly) revealed, if any? (multi_select; responses: outcomes_of_future_events, causal_past_events_or_backstory, motivations_or_interior_states, ontological_status_of_world_or_entities, none_significant).
- **REV_DIS_014 — Resolution Explicitness of Core Questions**: To what degree does the story explicitly answer its central narrative questions by the end? (ordinal; responses: key_questions_left_open_or_ambiguous, partial_or_tentative_answers, clear_and_explicit_answers_to_central_questions).
- **REV_DIS_016 — Information Source Diversity**: Through which channels does the story introduce significant new information to the reader? (multi_select; responses: narrator_direct_exposition, character_dialogue, internal_monologue_free_indirect_style, documents_or_media_within_story, environmental_or_scenic_clues, frame_narrator_or_later_commentary).
- **REV_DIS_017 — Presence of Meta-Revelation**: Does the story include any revelation about its own narrative status (e.g., that events are fictional, simulated, archived, or part of an experiment)? (binary; responses: yes, no).
- **REV_DIS_018 — Character Knowledge Change Arc**: How strongly does the main viewpoint character's understanding of their situation change due to revelations over the course of the story? (scale; responses: 1, 2, 3, 4, 5).


## Events

What happens: event types, density, causality, schemas, escalation

### Event Composition and Texture

- **EVT_TYP_001 — Event Density per Text Length**: How densely packed with discrete events is the story relative to its length? (scale; responses: 1_very_sparse_few_events_over_many_words, 2_sparse, 3_moderate, 4_dense, 5_very_dense_events_every_few_sentences).
- **EVT_TYP_006 — Dominant Focal Level of Events**: At what social scale do most important events operate? (categorical; responses: individual_or_intimate_personal_scale, family_or_small_group_scale, community_or_institutional_scale, world_systemic_or_cosmic_scale).

### Event Density & Granularity

- **EVT_TYP_003 — Local vs Global Event Orientation**: Is the event structure primarily organized around discrete dramatized scenes or around broad summarized stretches of story-time? (categorical; responses: scene_based, summary_based, hybrid).

### Event Types and Modalities

- **EVT_TYP_004 — Event-type diversity**: How many distinct event modalities (action, social, mental, perceptual, environmental, institutional) does the story employ in a substantive way? (ordinal; responses: low_diversity, medium_diversity, high_diversity).

### Event Initiation and Stakes Profile

- **EVT_SCH_007 — Escalation of stakes domain breadth**: Over the course of events, do the stakes remain confined to a single domain, or expand from personal to wider social/cosmic domains? (categorical; responses: confined_to_single_domain, expand_from_personal_to_social_or_institutional, expand_to_cosmic_or_existential_scope, contract_from_broad_to_intimate).
- **EVT_TYP_008 — Event-time coverage of the main arc**: What is the primary length of story-world time covered by the main event sequence (excluding brief prologues/epilogues)? (ordinal; responses: single_scene_or_few_hours, single_day_and_night, several_days_to_months, multiple_years, nonlinear_or_deep_time_spanning_generations_or_epochs).

### Narrative Schemas and Global Arc

- **EVT_SCH_004 — Mode of resolution of the main event chain**: How is the central conflict or event chain brought to a close, if at all? (categorical; responses: resolved_through_external_action_or_intervention, resolved_through_internal_understanding_or_acceptance, partial_or_compromise_resolution, open_or_ambiguously_unresolved, catastrophic_or_irrevocably_negative_outcome).

### Narrative Schemas, Arc Shape, and Resolution

- **EVT_SCH_002 — Arc Completeness Relative to Implied Plot**: How much of the implied full plot does the text actually cover? (ordinal; responses: setup_only_or_preliminary_phase, partial_arc_with_cliffhanger_or_open_crisis, full_arc_to_local_resolution, multi_phase_arc_extending_well_beyond_prompt).
- **EVT_SCH_003 — Strength of Event Escalation**: How strongly do events escalate in stakes or intensity over the course of the narrative? (scale; responses: 1_almost_flat_little_or_no_escalation, 2_mild_escalation, 3_moderate_escalation, 4_strong_escalation, 5_relentless_or_steep_escalation).
- **EVT_SCH_006 — Use of Explicit Frame Narrative**: Does the story use an explicit frame (e.g., a narrator in the present recounting past events to an audience)? (binary; responses: no_frame_or_minimal_metacommentary, has_explicit_frame_story_or_recounting_context).
- **EVT_SCH_008 — Dominant Event Initiation Source**: What primarily triggers new major events across the story? (categorical; responses: character_choice_and_desire, external_forces_or_accidents, institutional_or_task_driven_demands, supernatural_or_technological_intrusion, gradual_situational_drift_without_clear_incidents).

### Causal Structure and Connectivity

- **EVT_CAU_001 — Explicitness of causal links**: How explicitly does the narration mark cause-and-effect relations between events? (categorical; responses: predominantly_explicit_causation, mixed_explicit_and_implicit, predominantly_implicit_or_inferred, weak_or_non_causal_associative_sequence).
- **EVT_CAU_002 — Continuity of the main causal chain**: To what extent does a single, continuous causal chain carry through from inciting incident to ending, versus multiple disjoint or restarting chains? (scale; responses: 1, 2, 3, 4, 5).
- **EVT_CAU_003 — Attention to unintended consequences**: Does the story foreground downstream, unintended consequences of characters' actions as significant events? (binary; responses: no_salient_unintended_consequences, prominent_unintended_consequences).

### Causal Structure and Event Connectivity

- **EVT_CAU_004 — Perceived Determinism of Outcomes**: Does the narrative present outcomes as fated/inevitable, contingent, or somewhere in between? (ordinal; responses: strongly_fated_or_inevitable, mixed_fate_and_contingency, highly_contingent_or_random_feeling).
- **EVT_CAU_005 — Primary Agent of Causal Momentum**: Whose actions most strongly drive the causal chain of the story? (categorical; responses: protagonist_or_focal_character_driven, antagonist_or_opposing_character_driven, system_environment_or_institution_driven, balanced_or_shifting_among_multiple_agents).
- **EVT_CAU_006 — Treatment of Alternative or Repeated Event Paths**: How does the story handle multiple versions or repetitions of similar events? (categorical; responses: single_linear_history_no_alternatives, explicit_multiple_versions_or_branches_of_events, loops_or_resets_of_the_same_event_sequence, ritual_repetition_of_a_template_event_with_variation).

### Temporal Arrangement of Events

- **EVT_TYP_009 — Balance of present-time versus flashback events**: Relative to the story's discourse time, are most events shown in present progression, in analeptic flashback, or in a balanced alternation? (categorical; responses: mostly_present_progression, balanced_present_and_past, mostly_past_or_recollected_events).

### Causal Structure & Initiation

- **EVT_CAU_008 — Primary Progression Logic**: What is the primary logic by which events are ordered and connected? (categorical; responses: strict_cause_effect, chronological_sequence, associative_thematic, nonlinear_fragmented).
- **EVT_CAU_018 — Use of Repetition or Variants as Event Engine**: Does the narrative construct multiple alternative or repeated versions of essentially the same core event (e.g., executions, loops, trial iterations) as a structural device? (binary; responses: yes, no).

### Temporal Handling & Event Novelty

- **EVT_CAU_016 — Temporal Scope of Events**: Over what span of story-time do the narrated events mainly extend? (categorical; responses: hours_to_days, weeks_to_months, years, multi_decade/generational, timeless/ahistorical).
- **EVT_CAU_017 — Event Novelty Orientation**: On a 1–5 scale, how strongly does the story lean on surprising, schema-breaking events versus familiar, predictable ones (1 = very predictable, 5 = highly surprising)? (scale; responses: 1, 2, 3, 4, 5).

### Narrative Schemas & Structural Completeness

- **EVT_SCH_010 — Global Narrative Schema**: Which high-level narrative schemas are structurally central to the story? (multi_select; responses: quest/journey, investigation/mystery, transformation/redemption, siege/ordeal, slice_of_life, trial/test/game, heist/caper, frame_confession/memoir).
- **EVT_SCH_011 — Structural Completeness of Event Arc**: How much of a full dramatic arc (setup–rising action–climax–resolution) does the story actually stage? (ordinal; responses: setup_only, partial_arc, full_arc_with_resolution).

### Escalation, Climax, and Resolution

- **EVT_SCH_013 — Tension Escalation Pattern**: What overall pattern best describes how stakes and intensity of events evolve across the story? (categorical; responses: rising_tension_to_climax, episodic_peaks, flat_low_tension, anti_climactic/deflationary).
- **EVT_SCH_014 — Clear Single Climactic Event**: Is there a single, clearly foregrounded climactic event that the narrative unmistakably builds toward? (binary; responses: yes, no).


## Perspective

Narration: point of view, focalization, dialogue, narrative voice, interior access

### Narrative Person and Narrator

- **PER_POV_001 — Dominant narrative person**: What is the primary grammatical person used by the main narrator across the story? (categorical; responses: first_person, second_person, third_person, mixed_no_dominant).
- **PER_POV_007 — Embedded documents as narrative voices**: Does the story incorporate letters, logs, transcripts, articles, or similar documents as significant alternate narrative channels? (binary; responses: present, absent).
- **PER_POV_008 — Degree of heteroglossia and polyphony**: How many distinct sociolects, registers, or idiolects does the narrative meaningfully orchestrate? (scale; responses: 1, 2, 3, 4, 5).
- **PER_POV_009 — Frequency of direct address to the reader**: How often does the text directly address the reader ('you') as an addressee outside the story? (ordinal; responses: never, occasional_asides, frequent_or_structural).

### Narrative Person and Configuration

- **PER_POV_003 — Narrator's diegetic status**: What is the narrator's relationship to the story world: are they a protagonist, a minor participant, an external observer, or a collective/institutional voice? (categorical; responses: autodiegetic_protagonist, homodiegetic_minor_character, heterodiegetic_external, collective_or_institutional_voice).

### Focalization Depth and Breadth

- **PER_FOC_001 — Depth of interior access to characters**: How deep into characters' inner life does the non-dialogue narration regularly go? (scale; responses: 1, 2, 3, 4, 5).
- **PER_FOC_002 — Breadth of focalization across characters**: Across the story, how many distinct characters' inner experiences does the narration give direct access to? (categorical; responses: single_focal_character, dual_focal_characters, multiple_small_set_3_to_5, many_or_godseye).

### Focalization and Interiority

- **PER_FOC_003 — Narrative distance (closeness of narrative voice to focalizer)**: On a 1–5 scale, how close is the narrating voice to the focalizing consciousness in tone and access? (scale; responses: 1, 2, 3, 4, 5).
- **PER_FOC_005 — Intensity of free indirect discourse**: To what extent does the narration rely on free indirect discourse (especially in third person) to convey character consciousness? (scale; responses: 0_none, 1_rare_or_isolated_instances, 2_moderate_recurring_use, 3_frequent_dominant_narrative_mode).

### Narrator presence, reliability, and self-awareness

- **PER_FOC_007 — Narrator reliability**: How is the narrator's reliability presented? (categorical; responses: reliable_or_neutral_reporter, explicitly_unreliable_or_deceptive, ambiguous_or_contested_reliability).
- **PER_FOC_008 — Narrator presence/visibility**: How visible is the narrator as a distinct speaking presence (with opinions, personality, or direct address)? (scale; responses: 1_almost_invisible_narrator_minimal_intrusion, 2_rare_asides_or_stylistic_flourishes, 3_moderately_present_with_recurring_comments, 4_strongly_personalized_voice_guiding_interpretation, 5_highly_intrusive_narrator_almost_a_character_in_its_own_right).
- **PER_FOC_009 — Degree of explicit evaluative or moral commentary**: How frequently does the narrative voice supply explicit moral, ethical, or evaluative commentary on characters and events? (scale; responses: 1_none_or_very_subtle_value_judgments, 2_occasional_overt_moral_or_evaluative_comments, 3_regular_value_judgments_but_not_overwhelming, 4_frequent_moralizing_or_didactic_passages, 5_morally_commentative_voice_dominates_the_narration).

### Dialogue proportion, function, and style

- **PER_DIA_001 — Dialogue-to-narration proportion**: Roughly what proportion of the text consists of direct dialogue (quoted speech) versus narration and description? (scale; responses: 1_almost_no_dialogue_mostly_narration, 2_dialogue_is_rare_but_present, 3_balanced_mix_of_dialogue_and_narration, 4_dialogue_is_frequent_with_some_narrative_linking, 5_dialogue_dominates_with_minimal_narrative_exposition).
- **PER_DIA_002 — Dialogue tagging style**: How are speakers identified and managed in dialogue passages? (categorical; responses: standard_speech_tags_and_action_beats, sparse_or_minimal_tagging_relying_on_voice_or_turn_taking, experimental_or_ambiguous_tagging_with_unattributed_lines).
- **PER_DIA_003 — Primary functions of dialogue**: What main functions does dialogue serve in the story? (multi_select; responses: advance_plot_or_deliver_crucial_information, reveal_character_psychology_or_relationships, worldbuilding_or_background_exposition, philosophical_or_thematic_debate, comic_relief_or_tone_coloration).
- **PER_DIA_006 — Use of alternative dialogue-like forms**: Does the text incorporate dialogue-like communication in alternative formats (such as chat logs, transcripts, forum posts, letters, or reports) that function as conversation? (binary; responses: yes, no).

### Dialogue Style and Attribution

- **PER_DIA_005 — Balance of direct versus indirect speech**: Does the story mainly present speech as direct quotations, as indirect/reported speech, or mostly summarize conversation? (categorical; responses: primarily_direct_quoted_speech, mixed_direct_and_indirect_speech, primarily_indirect_or_summary_of_speech).


## Plot

Story structure: themes, conflicts, arcs, resolutions, moral content, narrative architecture

### Thematic Architecture

- **PLT_THM_001 — Number of Central Themes**: How many distinct central themes does the story develop in a sustained way? (categorical; responses: single_central_theme, two_primary_themes, multiple_disparate_themes).

### Thematic Structure and Unity

- **PLT_THM_004 — Thematic Domains**: Which thematic domains are centrally explored in the story's plot? (multi_select; responses: survival/fear, power/authority, justice/injustice, love/attachment, identity/selfhood, family/generation, faith/spirituality, class/economics, technology/science, nature/environment, art/creativity, grief/loss, guilt/redemption, violence/trauma, social systems/institutions).
- **PLT_THM_005 — Thematic Resolution Pattern**: By the end, how are the main thematic tensions treated? (categorical; responses: resolved (tensions largely settled or answered), partially_resolved (some progress but key tensions remain), unresolved (tensions deliberately left open), reframed/transcended (tension transformed into new understanding)).
- **PLT_THM_006 — Dominant Narrative Archetype**: Which classic narrative archetype best fits the story's main arc? (categorical; responses: quest/journey, voyage_and_return, rags_to_riches_or_education, rebirth/redemption, tragedy/fall_from_grace, overcoming_the_monster/disaster, comedy_of_errors/social_farse, investigation/mystery, coming_of_age/initiation, frame_confession_or_testimony, slice_of_life/vignette).
- **PLT_THM_007 — Archetype Blending**: Does the story clearly blend multiple recognizable archetypes? (binary; responses: no (mostly single archetype), yes (two or more archetypes substantially combined)).
- **PLT_THM_008 — Thematic Unity**: To what extent do subplots, set-pieces, and stylistic flourishes serve a central thematic concern? (scale; responses: 1, 2, 3, 4, 5).
- **PLT_THM_009 — Integration of Subplots with Theme**: If subplots exist, how directly do they echo or complicate the central theme? (categorical; responses: no_subplots, directly_thematically_parallel, thematically_contrasting/ironic, largely_thematically_independent).

### Thematic Structure

- **PLT_THM_003 — Abstract vs Concrete Thematic Orientation**: Are the dominant themes primarily about concrete social/material issues, inner psychology, metaphysical/cosmic questions, or a balanced mix? (categorical; responses: concrete_social, psychological, metaphysical_cosmic, balanced_mix).

### Conflict Type and Outcome

- **PLT_CON_001 — Primary Conflict Locus**: Is the central conflict primarily internal to a character, external, or equally both? (categorical; responses: internal, external, balanced_internal_external).
- **PLT_CON_004 — Antagonist Ontology**: What best describes the main opposing force in the story? (categorical; responses: single_individual_antagonist, multiple_individual_antagonists, impersonal_system_or_institution, impersonal_environment_or_disaster, internal_psychological_conflict, supernatural_or_cosmic_force).
- **PLT_CON_007 — Agency in Resolution**: Is the resolution of the central conflict driven mainly by the protagonist's deliberate choices or by events beyond their control? (categorical; responses: primarily_protagonist_choice, mixed_choice_and_chance, primarily_external_fate/chance).

### Conflict and Stakes

- **PLT_CON_002 — Core Conflict Types**: Which classic conflict dyads are instantiated as major drivers of the plot? (multi_select; responses: person_vs_person, person_vs_society, person_vs_nature, person_vs_self, person_vs_supernatural_or_tech, person_vs_fate_or_time).

### Conflict and Stakes

- **PLT_CON_003 — Stakes Domains at Risk**: Which domains are significantly at stake in the central conflict? (multi_select; responses: physical_survival_or_bodily_harm, personal_relationships_and_family, social_or_political_order, identity_or_psychological_integrity, moral_or_spiritual_salvation, cosmic_or_existential_meaning).

### Structural Arc Form

- **PLT_STR_001 — Global Arc Shape**: What overall structural shape does the plot follow? (categorical; responses: classic_rising_action_to_climax_to_denouement, episodic_or_serial_adventures, circular_or_return_to_start_state, fragmentary_or_elliptical, iterative_or_variation_on_a_scenario, deliberately_flat_or_anti_climactic).
- **PLT_STR_002 — Narrative Entry Frame**: How does the story enter its timeline with respect to the main events? (categorical; responses: chronological_from_earliest_relevant_event, in_medias_res_with_backstory_revealed_later, framed_or_retrospective_narration).
- **PLT_STR_003 — Density of Subplots**: How many substantive subplots or secondary arcs interweave with the main plot? (ordinal; responses: no_significant_subplots, one_or_two_minor_subplots, multiple_interwoven_subplots_or_ensemble_arcs).
- **PLT_STR_005 — Dominant Revelation Pattern**: What is the primary pattern by which new information and surprises are delivered? (categorical; responses: mystery_or_investigation_driven, dramatic_irony_reader_knows_more_than_characters, transparent_exposition_minimal_secrets, twist_or_reversal_focused, iterative_reframing_of_the_same_events).
- **PLT_STR_006 — Climax Placement**: Where, structurally, does the main climactic moment occur in the story? (categorical; responses: late_climax_near_end, central_climax_mid_story, multiple_climactic_peaks, no_clear_climactic_peak).

### Moral Stance and Closure

- **PLT_MOR_001 — Moral/Lesson Explicitness**: How overtly does the story articulate a moral, lesson, or prescriptive takeaway? (ordinal; responses: no_discernible_moral_or_thematic_judgment, implicit_moral_inferred_from_outcomes_and_tone, explicit_didactic_moral_or_authorial_comment).
- **PLT_MOR_003 — Ending Closure Type**: What kind of closure does the ending provide for plot and character arcs? (categorical; responses: closed_resolution_plot_and_fates_mostly_settled, open_ending_major_plot_threads_unresolved, ambiguous_or_interpretive_ending, cyclical_return_to_beginning_motif, cliffhanger_designed_to_lead_into_sequel).
- **PLT_MOR_004 — Protagonist Transformational Trajectory**: How does the primary protagonist change internally over the course of the story? (categorical; responses: positive_growth_or_enlightenment, negative_fall_or_corruption, mixed_or_partial_change, no_significant_internal_change).
- **PLT_MOR_006 — Degree of Closure**: On a 1–5 scale, how fully does the ending close down narrative questions and conflicts? (scale; responses: 1, 2, 3, 4, 5).
- **PLT_MOR_007 — Post-Climax Denouement Length**: How extended is the narrative after the main climactic event? (ordinal; responses: none_or_minimal (story ends immediately after climax), brief (a short scene or paragraph of aftermath), extended (multiple scenes/time jumps of aftermath/epilogue)).

### Moral and Ethical Framing

- **PLT_MOR_002 — Moral Polarity Toward Protagonist**: What evaluative stance does the narrative ultimately take toward its central protagonist? (categorical; responses: affirmative_heroic, critical_tragic_flaw, ambivalent_or_morally_mixed, subversive_or_antiheroic).

### Arc Shape and Temporal Structure

- **PLT_STR_007 — Tension Escalation Clarity**: On a 1–5 scale, how clearly does the story build and escalate narrative tension toward one or more climaxes? (scale; responses: 1, 2, 3, 4, 5).

### Stakes and Consequences

- **PLT_STR_009 — Primary Stakes Domain**: What is primarily at stake in the central conflict? (categorical; responses: physical_survival/bodily_harm, relationships/love/family, identity/sanity/psychic_integrity, social_order/community/institutions, cosmic/metaphysical_order, material_gain/reputation).
- **PLT_STR_010 — Stakes Breadth**: How broad are the consequences of failure or success in the central conflict? (ordinal; responses: intimate (affects only protagonist or small dyad), local (affects a family, team, or small community), societal (affects a city, nation, or large institution), global_or_cosmic (worldwide, planetary, or metaphysical stakes)).
- **PLT_STR_011 — Stakes Types Present**: Which types of stakes are meaningfully in play? (multi_select; responses: physical_survival, emotional/relational_loss, moral_or_spiritual_integrity, social_status/reputation, economic/security, knowledge/truth/reality_stability, ecological/planetary_health).


## Setting

Where and when: locations, time, atmosphere, world-building, spatial imagination

### Spatial Specificity and Scope

- **SET_LOC_005 — Dominant Spatial Scale**: What is the dominant spatial scale of the story's core action? (categorical; responses: intimate_or_bodily, household_or_local_block, urban_or_regional, planetary_or_cosmic, multi_scale_mixed).
- **SET_LOC_008 — Dominant Space Types**: Which types of spaces dominate the story's significant scenes? (multi_select; responses: domestic_private, public_social, natural_outdoor, institutional_or_workplace, virtual_or_digital).
- **SET_LOC_009 — Recurring Symbolic Anchor Settings**: Does the story repeatedly return to one or two key locations that function as symbolic anchors for its themes? (binary; responses: yes, no).
- **SET_LOC_010 — Ontological Ambiguity of Place**: How straightforwardly real vs ontologically unstable is the setting presented as being within the story? (categorical; responses: straightforward_mimetic, mildly_unreliable_or_magical, strongly_ambiguous_or_simulated).

### Spatial Specificity and Scale

- **SET_LOC_002 — Spatial Granularity Level**: How fine-grained is the story's depiction of physical space and geography? (ordinal; responses: 1_very_low, 2_low, 3_medium, 4_high).
- **SET_LOC_011 — Location Variety Scope**: How many distinct physical locales does the story meaningfully inhabit over its course? (ordinal; responses: 1_single_primary_location, 2_two_to_four_locales, 3_many_within_one_region, 4_multi_regional_or_international, 5_multiworld_or_multiverse).
- **SET_LOC_016 — Ontological Stability of Environment**: Does the setting obey stable, realist physics, or does it feature magical, speculative, or reality-fluid properties? (categorical; responses: realist_stable, realist_with_magical_intrusions, fully_speculative_but_rule_based, reality_fluid_or_unstable).
- **SET_LOC_018 — Setting Mobility Pattern**: How does the protagonist's relationship to place evolve structurally: mostly static, a one-way journey, a back-and-forth oscillation, or a return home transformed? (categorical; responses: static_single_hub, outward_journey_only, pendulum_home_away, spiral_departure_and_return).

### Spatial Specificity and Ontology

- **SET_LOC_003 — Geospatial Coherence**: How coherently mapped is the story's geography across its locations? (categorical; responses: single_coherent_region, multiple_regions_with_clear_map, collage_of_unconnected_locales, deliberately_fluid_or_shifting_geography).

### Setting Introduction and Spatial Anchoring

- **SET_LOC_004 — Opening Spatial Grounding**: How clearly does the story's opening ground the reader in a specific physical setting? (ordinal; responses: none_or_very_vague, minimal_local_details_only, clear_local_setting_but_limited_global_context, clear_local_and_global_spatial_context).

### Scale and Spatial Mobility

- **SET_LOC_007 — Spatial Mobility Pattern**: How much does the narrative move between distinct locations? (categorical; responses: single_primary_location, multiple_locations_within_one_area, travel_between_distant_regions_or_worlds).

### Types of Spaces and Spatial Ecology

- **SET_LOC_012 — Built vs Natural Setting Balance**: What is the balance between built (human-made) and natural environments in the story's settings? (categorical; responses: mostly_indoor_built_environments, mixed_built_and_natural, mostly_outdoor_natural_environments).

### World-Building and Infrastructure

- **SET_LOC_013 — Speculative World-Building Depth**: For speculative or non-mimetic settings, how deeply does the story elaborate systemic aspects of its world (technology, social orders, ecologies, metaphysics)? (scale; responses: 1, 2, 3, 4, 5).
- **SET_LOC_014 — Environmental and Ecological Emphasis**: To what extent does the story foreground landscape, climate, and ecological processes as part of the setting's logic? (scale; responses: 1, 2, 3, 4, 5).

### Temporal Setting and Structure

- **SET_TIM_015 — Temporal Setting Specificity**: How specifically is the time period of the story identified or implied? (categorical; responses: timeless_or_mythic, implied_period_only, explicit_historical_past, contemporary_realistic, near_future_speculative, far_future_or_deep_time).
- **SET_TIM_016 — Temporal Scaffolding Complexity**: How complex is the story's handling of time (flashbacks, jumps, parallel timelines)? (scale; responses: 1, 2, 3, 4, 5).

### Sensory Texture

- **SET_ATM_017 — Dominant Sensory Modalities**: Which sensory modalities does the story most frequently engage when rendering setting? (multi_select; responses: visual, auditory, olfactory, tactile, gustatory, kinesthetic).

### Atmosphere, Mood, and Symbolic Use of Setting

- **SET_ATM_019 — Setting–Plot Causal Role**: What best describes the relationship between setting and plot causality? (categorical; responses: backdrop_only, constraints_and_obstacles, active_agent_or_antagonist, structuring_symbolic_landscape).
- **SET_ATM_020 — Atmospheric Construction Techniques**: Which elements does the story most rely on to build atmosphere and mood in its settings? (multi_select; responses: weather_and_light, architecture_and_objects, nature_and_landscape, crowds_and_noise, decay_and_dirt, technology_and_media).
- **SET_ATM_022 — Setting as Psychological Mirror**: To what degree does the story use physical environment as a mirror or metaphor for characters' inner states? (scale; responses: 1, 2, 3, 4, 5).

### Setting–Plot Relationship

- **SET_ATM_003 — Setting Agency Level**: To what extent does the setting itself act as an agentive force affecting the plot? (categorical; responses: passive_backdrop, provides_constraints_or_opportunities, acts_as_active_antagonist_or_ally, functions_as_central_character_or_thematic_engine).

### Atmosphere and Mood

- **SET_ATM_004 — Dominant Setting Mood Qualities**: Which mood qualities does the setting most strongly and repeatedly convey? (multi_select; responses: cozy_safe, bleak_or_oppressive, uncanny_or_haunted, noir_or_gritty, sublime_or_awe_inspiring, neutral_or_matter_of_fact).

### Sensory and Atmospheric Texture

- **SET_ATM_005 — Sensory Density**: How dense is the sensory description of the setting across the narrative? (scale; responses: 1_minimal, 2_sparse, 3_moderate, 4_rich, 5_lush_overdetermined).
- **SET_ATM_013 — Dominant Environmental Mood**: What overall emotional tone does the setting most consistently evoke? (categorical; responses: mundane_realist, cozy_or_idyllic, bleak_or_desolate, uncanny_or_haunted, wondrous_or_sublime, satirical_or_grotesque).

### World-Building and Plot Linkage

- **SET_LOC_015 — Predominant Space Types**: Which categories of space (domestic, public, natural, institutional, liminal) are structurally important across the narrative? (multi_select; responses: domestic_private, public_urban_or_commercial, rural_or_wild_natural, formal_institutional, liminal_edges_and_transit).
- **SET_LOC_017 — Digital or Virtual Spaces as Places**: Do online, simulated, or otherwise non-physical environments function as significant settings? (binary; responses: yes, no).

### Temporal Setting and Anchoring

- **SET_TIM_002 — Temporal Anchoring Clarity**: How specifically anchored in time is the narrative? (ordinal; responses: no_temporal_markers, approximate_period_only, specific_dates_or_historical_events, multiple_distinct_time_periods_interwoven).


## Style

Language: figurative language, sentence structure, register, tone, allusion, prose texture

### Figurative Devices and Tropes

- **STY_FIG_001 — Figurative Device Density**: On a 1–5 scale, how densely does the passage use figurative language such as metaphor, simile, or personification relative to its length? (scale; responses: 1, 2, 3, 4, 5).
- **STY_FIG_002 — Dominant Figurative Device Type**: Which figurative device type is most frequently used in the passage? (categorical; responses: mostly_literal (no clear dominant trope), simile_dominant, metaphor_dominant, personification_or_prosopopoeia_dominant, mixed_no_clear_dominant).

### Figurative intensity and devices

- **STY_FIG_003 — Conventional vs fresh figurative language**: How original versus conventional are the figurative expressions overall? (ordinal; responses: 1 - mostly_clichéd_or_stock_phrases, 2 - mix_of_cliché_and_some_fresh_images, 3 - predominantly_fresh_and_inventive_images).
- **STY_FIG_004 — Presence of extended conceit**: Does the passage develop an extended, multi-step metaphor or conceit sustained over several sentences? (binary; responses: absent, present).
- **STY_FIG_005 — Recurrent metaphorical motif**: Does the passage use a recurring metaphorical motif (e.g., weight, music, machinery) that structures multiple images? (binary; responses: absent, present).

### Imagery and sensory grounding

- **STY_FIG_007 — Overall imageability**: How vividly and concretely can a reader visualize or sensorially imagine this passage? (scale; responses: 1 - very_low_imageability_mostly_abstract, 2 - low_imageability_with_sporadic_concrete_detail, 3 - moderate_imageability, 4 - high_imageability_rich_concrete_detail, 5 - extremely_vivid_and_sensorially_dense).
- **STY_FIG_009 — Concrete vs abstract lexis balance**: On a 1–5 scale, how much does the passage favor concrete, physical vocabulary versus abstract, conceptual vocabulary? (scale; responses: 1 - predominantly_abstract_terms, 2 - mostly_abstract_with_some_concrete, 3 - balanced_mix_of_concrete_and_abstract, 4 - mostly_concrete_with_some_abstract, 5 - overwhelmingly_concrete_and_thing-focused).

### Syntax and Structural Complexity

- **STY_CPX_002 — Predominant Sentence Length Band**: What is the predominant sentence length band in this passage (considering independent sentences, not dialogue turn breaks)? (categorical; responses: very_short_0_10_words, short_11_20_words, medium_21_35_words, long_36_50_words, very_long_51plus_words).
- **STY_CPX_005 — Dominant Clause-Combining Strategy**: How are clauses most often combined in this passage? (categorical; responses: paratactic_coordination_simple_chaining, hypotactic_subordination_nesting, balanced_mixture_no_clear_dominance).

### Syntactic Complexity and Prose Rhythm

- **STY_CPX_003 — Use of Sentence Fragments**: Does the passage make noticeable use of non-standard sentence fragments for effect? (binary; responses: absent_or_negligible, present_and_stylistically_significant).
- **STY_CPX_004 — Parataxis vs Hypotaxis Preference**: Is the passage's syntax predominantly paratactic (coordination and simple sequence) or hypotactic (subordination and embedding)? (categorical; responses: strongly_paratactic, mostly_paratactic, balanced, mostly_hypotactic, strongly_hypotactic).
- **STY_CPX_006 — Scene vs Summary Balance (Show vs Tell)**: Within the passage, is narration dominated by dramatized scenes (dialogue, action in real time) or by summary and exposition? (ordinal; responses: mostly_summary_or_tell, summary_leaning_mixed, balanced, scene_leaning_mixed, mostly_scene_or_show).

### Tone, Evaluation, and Narratorial Stance

- **STY_TON_001 — Dominant Tonal Register**: What is the dominant tonal register conveyed by the narrative voice in this passage? (categorical; responses: neutral_reportorial, comic_or_ironic, lyrical_or_meditative, dark_or_gothic, hardboiled_or_noir, academic_or_analytic, satirical_or_baroque).
- **STY_TON_002 — Evaluative Commentary Density**: On a 1–5 scale, how often does the narrator explicitly judge, praise, or condemn characters and events rather than describing them neutrally? (scale; responses: 1, 2, 3, 4, 5).

### Tone, Register, and Voice

- **STY_TON_005 — Voice Markedness**: How stylistically marked or idiosyncratic is the narrative voice? (ordinal; responses: plain_neutral_minimally_marked, moderately_marked_distinct_but_not_extreme, highly_idiosyncratic_strong_dialect_or_mannerism).

### Sound Patterning and Cadence

- **STY_TON_006 — Sound Patterning Prominence**: How prominent are deliberate sound patterns such as alliteration, assonance, rhyme, or rhythmic repetition in the prose? (ordinal; responses: minimal, subtle_or_background, noticeable, dominant_feature).
- **STY_TON_007 — Rhythmic Contrast Strategy**: Which description best fits the passage's rhythm in terms of alternation between long and short units? (categorical; responses: mostly_even_rhythm, mostly_long_periodic_sentences, mostly_short_punchy_sentences, strong_contrast_between_long_and_short).

### Allusion and Intertextual Texture

- **STY_ALL_002 — Primary Allusion Domain**: What is the primary domain from which allusions in this passage are drawn? (categorical; responses: classical_or_literary_canon, religious_mythological_scriptural, historical_political_military, pop_culture_media_entertainment, scientific_technical_philosophical, commercial_brands_products, no_significant_allusions).
- **STY_ALL_003 — Allusion Obscurity Level**: How specialized or obscure are the allusions used in the passage? (ordinal; responses: common_accessible_references_most_readers_will_know, mixed_common_and_specialist_references, esoteric_specialist_references_requiring_niche_knowledge).
- **STY_ALL_005 — Meta-Discursive Commentary on Texts**: Does the passage include explicit commentary about stories, genres, or the act of writing/reading itself? (binary; responses: absent, present).
- **STY_ALL_006 — Degree of Genre Pastiche**: To what extent does the passage adopt a recognizable genre or authorial style as pastiche? (categorical; responses: none_straight_style_without_pastiche, light_genre_shading_or_influence, strong_deliberate_pastiche_of_specific_genre_or_author).

### Allusion and Intertextual Reference

- **STY_ALL_004 — Primary Function of Allusion**: What is the primary rhetorical function served by the allusions in this passage? (categorical; responses: worldbuilding_or_setting_color, characterization_or_interiority, humor_or_irony, argument_or_analogy, theme_signposting_or_moral_commentary).

### Sentence architecture and complexity

- **STY_CPX_010 — Mean sentence length category**: What is the approximate average sentence length in this passage? (categorical; responses: short_under_12_words, medium_12_to_20_words, long_21_to_30_words, very_long_over_30_words).
- **STY_CPX_011 — Syntactic subordination depth**: How complex are the sentences in terms of nested subordinate and relative clauses? (scale; responses: 1 - only_simple_or_single-clause_sentences, 2 - mostly_simple_with_rare_subordination, 3 - regular_but_shallow_subordination, 4 - frequent_multi-clause_sentences_with_embedding, 5 - very_high_hypotaxis_with_deeply_nested_clauses).
- **STY_CPX_012 — Sentence-structure repertoire**: Which structural patterns are used prominently in the sentences? (Select all that apply.) (multi_select; responses: frequent_fragments_or_elliptical_clauses, frequent_parallel_or_list-like_structures, frequent_periodic_or_suspensive_sentences, frequent_loose_multi-clause_chains, frequent_parenthetical_or_dash-inserted_asides).
- **STY_CPX_013 — Parenthetical aside frequency**: How often does the narrator insert parenthetical asides (in parentheses, dashes, or commas) that break the main syntactic flow? (ordinal; responses: 1 - none_or_very_rare, 2 - occasional_but_not_structural, 3 - frequent_and_stylistically_characteristic).

### Lexical register and allusion

- **STY_ALL_015 — Lexical register and consistency**: What is the predominant lexical register of the passage, and how consistent is it? (categorical; responses: consistently_colloquial_or_slangy, consistently_neutral_conversational_standard, consistently_elevated_or_literary, mixed_register_with_frequent_code_switching).
- **STY_ALL_016 — Latinate vs Anglo-Saxon lexical flavor**: On a 1–5 scale, does the passage lean toward short, Anglo-Saxon words or longer, Latinate/learned vocabulary? (scale; responses: 1 - strongly_Anglo-Saxon_simple_words, 2 - somewhat_Anglo-Saxon_leaning, 3 - balanced_mix, 4 - somewhat_Latinate/learned_leaning, 5 - strongly_Latinate_polysyllabic_and_technical).
- **STY_ALL_017 — Allusion density**: How densely does the passage employ explicit allusions to external texts, myths, history, brands, or cultural artifacts? (scale; responses: 1 - no_clear_allusions, 2 - one_or_two_minor_allusions, 3 - several_allusions_but_not_dominant, 4 - frequent_allusions_that_shape_the_passage, 5 - very_dense_allusive_texture_relying_on_external_references).
- **STY_ALL_018 — Allusion domain diversity**: What kinds of allusive domains does the passage draw on? (Select all that apply.) (multi_select; responses: religious_or_mythological, historical_or_political, literary_or_high_cultural, pop_culture_or_brand_names, scientific_or_technical_disciplines, self_referential_or_meta-textual).
- **STY_ALL_019 — Jargon and technical terminology usage**: How prominent is domain-specific jargon or technical terminology in the passage? (ordinal; responses: 1 - none_or_negligible_jargon, 2 - occasional_technical_terms_for_flavor, 3 - frequent_jargon_as_part_of_voice, 4 - dense_technical_register_central_to_style).

### Tone and evaluative stance

- **STY_TON_020 — Evaluative stance intensity**: How strongly does the narrative voice overtly judge, praise, or condemn characters and situations? (scale; responses: 1 - almost_purely_descriptive_no_overt_judgment, 2 - mildly_evaluative_at_moments, 3 - moderately_evaluative_throughout, 4 - strongly_evaluative_with_regular_labels_and_asides, 5 - intensely_polemical_or_moralizing).
- **STY_TON_021 — Predominant tonal quality**: What is the dominant tonal quality of the passage? (categorical; responses: earnest_or_lyrical, ironic_or_wry, detached_or_clinical, comic_or_satirical, gothic_or_horror_inflected, highly_variable_no_single_dominant_tone).
- **STY_TON_023 — Use of irony and humor**: To what extent does the passage employ irony, sarcasm, or humor as a stylistic device? (ordinal; responses: 1 - entirely_straightfaced_no_discernible_humor, 2 - occasional_light_humor_or_irony, 3 - pervasive_ironic_or_comic_stance).

### Rhythm and sound patterning

- **STY_TON_024 — Rhythmic markedness of prose**: How noticeable and patterned is the rhythm of the prose (e.g., through repetition, balanced clauses, cadence)? (scale; responses: 1 - flat_or_irregular_rhythm_no_stylistic_patterning, 2 - mild_rhythmic_shaping_in_places, 3 - moderate_rhythmic_patterning, 4 - strongly_cadenced_or_musical_prose, 5 - highly_orchestrated_rhythm_central_to_effect).
- **STY_TON_025 — Sound patterning devices**: Which sound patterning devices are salient in this passage? (Select all that apply.) (multi_select; responses: alliteration_prominent, assonance_or_consonance_prominent, occasional_internal_or_end_rhyme, onomatopoeia_or_sound_imitations, no_conscious_sound_patterning).

### Narrative exposition and structural texture

- **STY_TON_027 — Meta-narrative or self-reflexive commentary**: Does the narrative voice explicitly comment on its own storytelling, artificiality, or constraints? (binary; responses: absent, present).
- **STY_TON_028 — Framing device type**: What framing device, if any, structures the passage? (categorical; responses: no_explicit_frame_plain_narration, documentary_or_bureaucratic_frame_reports_letters_forms, epistolary_or_diary_frame, oral_tale_or_folktale_frame_storyteller_addressing_audience, academic_or_essayistic_analytic_frame, instructional_or_meta_process_frame_about_how_to_tell_story).
- **STY_TON_029 — Information density per sentence**: How much distinct narrative or conceptual information is packed into each sentence on average? (scale; responses: 1 - very_sparse_each_sentence_carries_one_simple_idea, 2 - relatively_sparse_with_few_ideas_per_sentence, 3 - moderate_density_two_or_so_ideas_per_sentence, 4 - dense_sentences_often_layering_several_ideas_or_details, 5 - very_dense_sentences_with_many_clauses_references_and_shifts).


## Situatedness

How the story positions itself in literary space: genre affiliation and fidelity, metafictional self-awareness, intertextuality, structural ambition, thematic self-consciousness, and its assumed reader.

### Genre Affiliation, Fidelity, and Tone

- **SIT_GEN_001 — Primary Genre Category**: What is the story's primary genre classification based on its dominant setting, plot devices, and reader expectations? (categorical; responses: realist_contemporary, historical_realist, science_fiction, fantasy, horror, mystery_detective, thriller_suspense, romance, comedy_satire, myth_fable_fairy_tale, literary_realist_fiction, multi_genre_blend, nonfictional_mode_pastiche_or_essayistic).
- **SIT_GEN_002 — Genre Fidelity Mode**: How does the story relate to the conventions of its primary genre? (categorical; responses: straight_genre_fulfillment, crossgenre_blend, genre_subversion_inversion, genre_frame_with_different_primary_focus, genre_agnostic_experimental).
- **SIT_GEN_003 — Genre Signal Timing**: How early in the story does the text clearly signal its primary genre to the reader? (ordinal; responses: immediate (within opening paragraph), early (within the first scene/page), mid-story (after some neutral buildup), late/ambiguous (genre only clear near the end or never fully fixed)).
- **SIT_GEN_004 — Tone Toward Genre Conventions**: What is the dominant tonal stance the story takes toward its own genre conventions? (categorical; responses: earnest_sincere, lightly_ironic_playful, parodic_or_spoofing, critical_or_deconstructive, nostalgic_reverent, ambivalently_mixed).
- **SIT_GEN_005 — Narrated Genre Awareness**: To what degree does the narration show explicit awareness of operating within a genre (e.g. by naming tropes or commenting on them)? (ordinal; responses: no_explicit_genre_awareness, implicit_winks_or_subtle_signals, overt_commentary_on_genre_tropes).

### Genre Orientation and Use

- **SIT_GEN_006 — Plot vs Atmosphere Orientation**: Is the story's use of genre more driven by plot mechanics or by mood and atmosphere? (ordinal; responses: 1-Strongly plot-driven, 2-Mixed but leaning plot, 3-Balanced, 4-Mixed but leaning atmosphere, 5-Strongly atmosphere-driven).
- **SIT_GEN_009 — Assumed Reader Competence**: What level of genre or literary competence does the story assume of its reader? (categorical; responses: General reader (no specialized knowledge assumed), Genre-savvy reader (expects familiarity with specific genre tropes), Literary-educated reader (expects comfort with complex structures/allusions), Insider/series reader (expects prior knowledge of specific fictional universe)).
- **SIT_GEN_010 — Moral / Philosophical Weighting**: Relative to entertainment, how important are moral or philosophical arguments in the story's overall design? (scale; responses: 1, 2, 3, 4, 5).

### Metafiction and Narrative Self-Awareness

- **SIT_MET_004 — Fourth-Wall Permeability**: To what extent does the story break or blur the boundary between story-world and reader? (ordinal; responses: 1-No fourth-wall breaking (reader never acknowledged), 2-Implicit winks or aside-like tonal gestures, 3-Occasional direct address or acknowledgement of reader, 4-Consistent or radical fourth-wall violations).
- **SIT_MET_006 — Embedded Storytelling Scenes**: Does the story include significant in-world acts of storytelling (characters telling stories, reading letters, viewing media) that shape its meaning? (ordinal; responses: 0-None, 1-Minor (brief anecdote or reference), 2-Moderate (one substantial embedded story or document), 3-Extensive (multiple or structurally central embedded narratives/documents)).

### Metafiction & Narrative Self-Reflexivity

- **SIT_MET_002 — Fourth-Wall Breaking**: Does the narration or a character directly address the reader or audience as such? (binary; responses: no direct address, yes, direct address present).
- **SIT_MET_005 — Ontological Play & Reality Instability**: How does the story treat the stability of its fictional reality (e.g., dreams, simulations, nested fictions)? (categorical; responses: stable mimetic reality (no questioning of what is real), single speculative layer but ontologically stable (e.g., one magical or SF premise taken as given), ambiguous/unstable reality (reader encouraged to doubt whether events are real, dreamt, simulated, etc.), multiple explicit reality layers or nested fictions (stories, simulations, or games within the world, with movement between levels)).

### Intertextuality & Relation to Tradition

- **SIT_MET_009 — Attitude Toward Literary Tradition**: How does the story position itself emotionally and critically toward the literary or mythic traditions it engages? (categorical; responses: reverent/continuist (aims mainly to honour, preserve, or smoothly extend tradition), critical/revisionist (explicitly reinterprets or challenges inherited stories), parodic/irreverent (treats tradition primarily as material for jokes or send-up), eclectic/agnostic (borrows elements without clear evaluative stance toward the sources)).
- **SIT_MET_202 — Intertextual Strategy Types**: What kinds of intertextual engagement with other works or traditions does the story employ? (multi_select; responses: explicit_named_reference_to_specific_texts_or_authors, retelling_or_reframing_of_specific_canonical_story, stylistic_pastiche_of_identifiable_author_or_period, use_of_mythological_or_religious_source_material, self_referential_links_to_other_works_in_same_storyworld).

### Intertextuality and Relation to Tradition

- **SIT_MET_008 — Reference Explicitness**: Are intertextual gestures primarily explicit name-checks or more diffuse, generic echoes? (categorical; responses: None (no discernible references), Primarily explicit named references (titles, authors, specific works), Primarily implicit echoes (genres, archetypes, unnamed myths), Balanced mix of explicit and implicit).

### Literary Register & Structural Ambition

- **SIT_MET_012 — Literary Ambition Signaling**: What kind of literary ambition does the story appear to signal in terms of market positioning and aesthetic aim? (categorical; responses: primarily genre entertainment (plot- and trope-driven, minimal overt thematic or stylistic ambition), crossover genre with literary aspirations (genre frame but clear stylistic/thematic ambition), mainstream literary fiction (character and theme foregrounded over genre engines), formally experimental/avant-garde (structure or language foregrounded over conventional readability)).

### Metafiction and Narrative Self-Consciousness

- **SIT_MET_102 — Ending-Level Self-Commentary on Story**: Does the ending explicitly comment on the act of storytelling, narrative closure, or the status of this text as a story? (binary; responses: no, yes).
- **SIT_MET_103 — Embedded Narrative Structures**: Does the story incorporate stories-within-the-story, such as framed tales, letters, reports, or other internal texts that characters tell or read? (categorical; responses: none, single_embedded_narrative_or_document, multiple_embedded_narratives_or_documents).
- **SIT_MET_104 — Narrator Address Mode**: How, if at all, does the narrator address a 'you' in the text? (categorical; responses: no_direct_address, generic_second_person_as_generalization, direct_address_to_actual_reader, address_to_diegetic_listener_only).

### Literary Ambition, Style, and Structural Experimentation

- **SIT_MET_301 — Perceived Literary Ambition in Prose Style**: How marked and 'literary' is the prose style in terms of figurative language, rhythm, and syntactic complexity? (scale; responses: 1, 2, 3, 4, 5).
- **SIT_MET_302 — Structural Experimentation Level**: How conventional or experimental is the story's overall structural arrangement (timelines, sections, points of view)? (ordinal; responses: simple_linear_single_strand, framed_or_mildly_non_linear, strongly_fragmented_or_formally_experimental).
- **SIT_MET_303 — Thematic Explicitness and Moralizing**: How explicitly does the story articulate its themes or morals in the narration or character speech? (scale; responses: 1, 2, 3, 4, 5).

### Assumed Reader Knowledge and In-Group Positioning

- **SIT_MET_402 — Required External Knowledge Level**: How much non-everyday external knowledge (historical, theoretical, niche cultural) is required to fully understand the story's stakes or references? (ordinal; responses: none_beyond_everyday_life, some_background_helpful_but_not_essential, substantial_background_required_for_full_comprehension).
- **SIT_MET_403 — Jargon and In-Group Reference Density**: How densely does the story use specialized jargon, acronyms, or insider cultural references without explanation? (ordinal; responses: none_or_minimal, moderate_and_mostly_explained, dense_and_largely_unexplained).

### Thematic Self-Awareness and Moral Stance

- **SIT_MET_501 — Narratorial Thematic Commentary Presence**: Does the narrator explicitly comment on the story's themes, lessons, or the meaning of events beyond characters' situated perspectives? (binary; responses: no, yes).


## Temporal Structure

Time handling: duration, order, pacing, frequency, temporal manipulation

### Temporal Span and Pacing

- **TMP_DUR_002 — Narrative Time Compression**: How compressed is the narrative relative to its story-time span (how much calendar time is covered per page on average)? (scale; responses: 1, 2, 3, 4, 5).

### Pacing, Scene/Summary, and Frequency

- **TMP_DUR_004 — Dominant pacing mode**: Which pacing mode dominates the narrative? (categorical; responses: scene_dominant, mixed_no_clear_dominant, summary_dominant, montage_or_episode_chain).

### Temporal Anchoring and Time Pressure

- **TMP_DUR_006 — Use of Iterative or Habitual Narration**: Does the narrative explicitly use iterative or habitual constructions (e.g., 'every Sunday we would...', 'for years she always...') to summarize repeated events? (binary; responses: yes, no).
- **TMP_DUR_009 — Density of Explicit Time Markers**: How frequently does the narrative use explicit temporal markers or transitions such as 'later that night', 'the next morning', 'weeks passed'? (scale; responses: 1, 2, 3, 4, 5).
- **TMP_DUR_010 — Typical Inter-Scene Time Jump Magnitude**: What is the typical magnitude of time that elapses between consecutive scenes or sections? (categorical; responses: continuous_or_near_continuous (minutes), hours_to_single_day, multi_day_to_few_weeks, months_or_longer_between_scenes).

### Pacing, Scene vs Summary, and Ellipsis

- **TMP_DUR_007 — Ellipsis frequency category**: How frequently does the narrative leap over substantial stretches of story time via ellipsis (e.g., 'weeks passed', 'years later') without narrating or closely summarizing intervening action? (categorical; responses: minimal_ellipses, some_ellipses, frequent_large_ellipses).

### Temporal Anchoring and Segmentation

- **TMP_DUR_008 — Precision of temporal anchoring**: How precise are the explicit temporal markers (dates, times, seasons) used to locate events in time? (ordinal; responses: 1_vague_or_no_markers, 2_seasonal_or_general_period_markers, 3_relative_day_and_duration_markers, 4_exact_calendar_dates_and_clock_times).

### Temporal Perspective and Tense

- **TMP_DUR_011 — Dominant Narrative Tense**: In what tense is the bulk of the narrative discourse written? (categorical; responses: past, present, future, mixed_or_shifted).
- **TMP_DUR_012 — Narrator's Temporal Distance from Events**: From what temporal vantage point does the narrator tell the story relative to the events (simultaneous or retrospective)? (categorical; responses: simultaneous_or_ongoing (narration_occurs_as_events_unfold), slightly_retrospective (days_to_few_years_after), distant_retrospective (many_years_or_decades_after), multiple_temporal_vantages_mixed).

### Chronological Ordering and Anachrony

- **TMP_ORD_001 — Global Chronological Structure**: How closely does the order of presented events follow chronological story-time order? (categorical; responses: strictly_chronological, mostly_chronological_with_rare_flashbacks, chronological_spine_with_frequent_flashbacks, strongly_non_linear_or_fragmented, reverse_chronology_dominant).
- **TMP_ORD_004 — Depth of Flashback Nesting**: How deeply are flashbacks nested inside other temporal layers? (ordinal; responses: no_flashbacks, single_level_flashbacks_only, multi_level_nested_flashbacks).
- **TMP_ORD_005 — Backstory Placement Strategy**: Where in the narrative are key backstory revelations concentrated? (categorical; responses: front_loaded_exposition, evenly_interleaved_throughout, withheld_until_late_reveal, minimal_or_implict_backstory_only).
- **TMP_ORD_010 — Degree of Chronological Discontinuity**: How often and how sharply does the narrative jump across time in ways that disrupt straightforward chronological flow? (scale; responses: 1, 2, 3, 4, 5).

### Chronological Order and Anachrony

- **TMP_ORD_002 — Anachrony intensity**: On a 1–5 scale, how heavily does the narrative rely on explicit flashbacks or flash-forwards as structural devices? (scale; responses: 1_no_real_anachrony, 2_rare_or_minor_flashbacks, 3_regular_flashbacks_supporting_main_line, 4_frequent_or_extended_anachrony, 5_dominant_anachronic_structure).
- **TMP_ORD_007 — Number of interwoven temporal strands**: How many distinct temporal strands (e.g., periods or lifelines) are interwoven in the discourse, as opposed to appearing only in isolated flashback blocks? (categorical; responses: single_strand, two_main_strands_braided, three_or_more_strands_braided).

### Chronological Order, Frames, and Anachrony

- **TMP_ORD_012 — Explicit time loops or multi-version retellings**: Does the story explicitly present multiple distinct versions or iterations of essentially the same time interval (e.g., execution morning, restaurant lunch), treated as alternates or loops rather than simple memories? (binary; responses: yes, no).
- **TMP_ORD_014 — Ending temporal scope**: Relative to the main line of events, where in story time does the narrative end? (categorical; responses: ends_at_or_just_after_main_climax_no_forward_jump, ends_with_brief_forward_epilogue_or_flashforward, ends_before_external_resolution_mid_arc_or_cliffhanger, ends_at_distant_future_or_far_past_vantage_summarizing_long_term).

### Temporal Devices, Perspective, and Transitions

- **TMP_ORD_011 — Dreams/visions as temporal distortion**: Does the narrative include extended dream or vision sequences that noticeably distort or suspend ordinary time (e.g., timeless realms, deep-time glimpses, compressed life reviews)? (binary; responses: no_significant_dream_time, significant_dream_or_vision_time).

### Frames, Loops, and Narrative Frequency

- **TMP_ORD_008 — Temporal Loop or Reset Pattern**: Does the narrative explicitly reset time to an earlier point (looping the same period), and how is this structured? (multi_select; responses: no_explicit_temporal_loop, same_day_or_hour_resets (Groundhog_Day_style), simulation_or_experiment_resets, branching_restarts_from_key_decision_point, structure_as_infinite_or_unresolved_loop).
- **TMP_ORD_009 — Dominant Narrative Frequency Mode**: Which narrative frequency mode is dominant in presenting main events (how often events are narrated vs occur)? (categorical; responses: singulative (events_told_once_as_they_occur), iterative (repeated_events_summarized_as_one), repeating (same_event_retold_multiple_times), mixed_without_single_dominant_mode).

### Global Temporal Span and Biographical Scope

- **TMP_DUR_021 — Character aging and biographical scope**: How much of the focal character(s)' life-course does the story explicitly cover? (categorical; responses: no_significant_aging_single_life_phase, single_character_across_multiple_life_stages, multi_generational_or_system_level_history).

### Temporal Markers, Anchoring, and Transitions

- **TMP_DUR_018 — Use of seasons and cyclical time as structuring devices**: To what extent does the story use seasons, festivals, or other cyclical temporal markers to structure its progression? (scale; responses: 1_no_or_negligible_reference_to_seasons_or_cycles, 2_occasional_season_or_holiday_mentions_not_structural, 3_seasons_or_cycles_mark_a_few_key_turning_points, 4_story_progression_is_strongly_keyed_to_seasons_or_festivals, 5_seasonal_or_cyclical_markers_form_the_primary_structural_scaffold).
- **TMP_DUR_019 — Prevalence of time-of-day markers**: How prominently and frequently does the narrative mark times of day (dawn, noon, dusk, midnight, specific hours) to pace scenes? (ordinal; responses: 1_almost_no_time_of_day_markers, 2_rare_mentions_of_general_times_of_day, 3_regular_but_not_systematic_time_of_day_marking, 4_frequent_and_specific_time_of_day_references, 5_time_of_day_markers_used_as_key_pacing_and_structural_cues).

### Time Pressure, Countdown, and Urgency

- **TMP_DUR_013 — Presence of explicit ticking clock or deadline**: Is there an explicit temporal deadline, countdown, or time-limited window that creates pressure on characters' actions (e.g., execution at 6 a.m., siege before dawn, exam at 9:00)? (binary; responses: yes, no).


## Agents

Characters: identities, roles, attributes, emotions, motivations, archetypes

### Character Inventory & Identity

- **AGENT_ID_001 — Scope of named human agents**: How many distinct named human characters (with proper names) appear in the narrative, excluding purely collective labels like 'the villagers'? (categorical; responses: 1, 2-3, 4-6, 7+).
- **AGENT_ID_004 — Types of non-human or collective agents**: Which kinds of non-human or collective entities are treated as agents (given actions, motives, or mental states)? (multi_select; responses: none, anthropomorphized animals, sentient supernatural entities (spirits, gods, curses, relics), AI or digital systems, institutions/personified organizations (e.g., 'the Consortium', 'the Church'), collective human groups as a single agent (e.g., 'the villagers', 'the Bigwigs')).
- **AGENT_ID_005 — Naming practice for the central character**: How is the central character primarily identified in the narration? (categorical; responses: named personal name (e.g., 'Maria', 'Leon'), unnamed but specific 'I/he/she' narrator, role/descriptor used as main identifier (e.g., 'the mother', 'the Anchor'), multiple or shifting identifiers (aliases, titles, different names in different contexts)).
- **AGENT_ID_007 — Opacity of central character at introduction**: How transparent or mysterious is the central character's identity and role at the moment they are first introduced? (categorical; responses: transparent (name, role, and situation given immediately), partially opaque (some key aspects withheld or unclear), highly opaque/mysterious (identity or role deliberately obscured for an extended time)).

### Character Inventory and Scale

- **AGENT_ID_002 — Secondary character density**: How many distinct secondary/supporting characters (beyond the major cast) appear in the story? (ordinal; responses: none or almost none (0–1), few (2–3), moderate (4–7), many (8 or more)).

### Naming and Reference

- **AGENT_ID_003 — Proportion of named vs. unnamed characters**: Overall, how are characters referred to: mostly by proper names, by role/descriptors, or a mix? (categorical; responses: almost all recurring characters are given proper names, mix of proper names and role-descriptors across both major and minor characters, only major characters have proper names; most minor figures are role-descriptors, few or no characters are named; most are referred to by roles or relational terms).

### Roles and Plot Agency

- **AGENT_ROLE_001 — Primary functional role of the central character**: Functionally, what role does the central character play in the story's action? (categorical; responses: active protagonist driving the main plot, observer/witness whose main role is to watch and report on others, antihero or antagonist whose actions are focalized, no single central figure (true ensemble of roughly equal agents)).
- **AGENT_ROLE_002 — Nature of principal antagonistic force**: What kinds of forces serve as the main opposition or obstacle to the central character(s)? (multi_select; responses: individual human antagonist(s), group of humans (mob, family, team), institution or system (church, corporation, legal regime), supernatural or cosmic entity, environment or nature (weather, landscape, disease not personified), internal psyche/mental state of the character).
- **AGENT_ROLE_003 — Plot agency level of the central character**: To what extent does the central character initiate and control key events, rather than mainly reacting to them? (ordinal; responses: mostly passive, mixed, mostly active).
- **AGENT_ROLE_004 — Use of collective human groups as agents**: Does the narrative treat any collective human group (e.g., 'the villagers', 'the Bigwigs', 'the kids') as a single agent with group-level intentions or feelings? (binary; responses: yes, no).
- **AGENT_ROLE_005 — Emphasis on social network versus solitude**: How much of the story's attention is on the central character's interactions within a broader social network versus their solitary experience? (ordinal; responses: low (mostly solitary), medium, high (ensemble-heavy)).
- **AGENT_ROLE_006 — Functions of secondary characters**: What main functions do secondary characters serve relative to the central character? (multi_select; responses: flat types or foils (e.g., bullies, bureaucrats, stock relatives), comic relief, mirrors or contrasts that highlight aspects of the central character, independent subplots or mini-arcs of their own, collective chorus or embodiment of 'society' or public opinion).
- **AGENT_ROLE_008 — Presence of a frame narrator distinct from main actors**: Is there a frame narrator whose primary role is to introduce, recount, or comment on another character's story, and who is distinct from the central acted-out protagonist? (binary; responses: yes, no).
- **AGENT_ROLE_009 — Primary epistemic agent (who interprets the story's mysteries)**: Who primarily discovers, interprets, or explains key information, puzzles, or moral meanings within the narrative? (categorical; responses: central character themselves, companion or sidekick figure, expert or institutional figure (detective, priest, scientist, court), external narrator/authorial commentary, no clear investigative agent (mysteries left largely uninterpreted)).

### Attributes, Introduction, and Interiority

- **AGENT_ATTR_001 — Dominant mode of introducing the central character**: In the first substantial appearance of the central character, what narrative device is primarily used to introduce them? (categorical; responses: external description (appearance/background summary), in-action event (we see them doing something significant), in-dialogue (they speak before being described), inner thought/monologue, through others' reports or gossip).
- **AGENT_ATTR_002 — Richness of physical description for the central character**: How detailed is the physical description of the central character across the narrative? (ordinal; responses: none/negligible, sparse (1-2 brief details), rich/elaborate).
- **AGENT_ATTR_003 — Social identity anchors for the central character**: Which kinds of social identity markers are used to situate the central character? (multi_select; responses: family roles (e.g., mother, son, aunt), occupation or specific skill (e.g., detective, physicist, wrestler), class, wealth, ethnicity, or nationality markers, psychological label or diagnosis (e.g., autistic, depressive, 'sensitive'), mythic or archetypal title (e.g., 'Anchor', 'paladin', 'final girl'), legal or institutional status (e.g., suspect, prisoner, veteran)).
- **AGENT_ATTR_004 — Explicit trait labeling**: Does the narration explicitly ascribe stable personality traits to the central character (e.g., 'she was shy and stubborn') rather than only showing them through behaviour? (binary; responses: yes, no).
- **AGENT_ATTR_005 — Primary technique for rendering inner life**: What is the primary narrative technique for representing the central character's inner thoughts and feelings? (categorical; responses: no direct access (behaviour and dialogue only), summary thought-report in narrator's voice, free indirect discourse (3rd person blending narrator and character voice), quoted interior monologue or stream-of-consciousness, first-person direct reporting of thoughts ('I thought...')).
- **AGENT_ATTR_006 — Psychological depth scale for central character**: On a 1–5 scale, how psychologically complex is the central character (considering contradictions, backstory, evolving self-understanding)? (scale; responses: 1, 2, 3, 4, 5).
- **AGENT_ATTR_009 — Closure of central character's psychological arc**: By the end, does the narrative present the central character's internal trajectory as having reached a clear resting point (even if tragic), rather than halting mid-crisis? (binary; responses: yes, no).

### Introduction and Backstory Placement

- **AGENT_ATTR_008 — Staggered vs. batch introduction of core cast**: Are core characters introduced gradually over time or in an early exposition cluster? (binary; responses: staggered introduction across the story, batch introduction early in the story).

### Emotional Expression

- **AGENT_EMO_009 — Dominant mode of emotional expression**: How are characters' emotions most commonly conveyed? (categorical; responses: explicit_emotion_labels, embodied_sensations_and_metaphors, behavioral_cues_and_action_only, consistently_ambiguous_or_suppressed).
- **AGENT_EMO_012 — Preferred cues for conveying emotional state**: Which textual cues are most commonly used to convey what characters are feeling? (multi_select; responses: bodily sensations or physiology (e.g., heartbeat, nausea, tight chest), facial expressions or gestures (e.g., frowns, smiles, posture), action choices and behavior (e.g., slamming doors, withdrawing, calling someone), metaphorical or environmental mirroring (weather, setting, or images echoing mood), dialogue content and tone (what and how characters speak)).

### Motivations & Goals

- **AGENT_MOT_003 — Dominant sources of motivation**: Which sources most strongly drive the central character's actions? (multi_select; responses: personal desire or ambition, ethical or ideological principles, social or familial obligations, trauma or past hurt, economic survival or material necessity, supernatural or external compulsion).
- **AGENT_MOT_004 — Evolution of motivations over time**: Does the central character's primary motivation clearly change or develop over the course of the narrative? (binary; responses: yes, no).
- **AGENT_MOT_011 — Explicitness of character motivations**: How explicitly are characters' motivations stated in the narration or dialogue? (ordinal; responses: mostly_implict_or_inferred, occasionally_stated_internally, frequently_spelled_out_in_dialogue_or_narration).
- **AGENT_MOT_012 — Typical motivation domains for major characters**: Which motivation domains most frequently drive major characters' actions? (multi_select; responses: survival_or_physical_safety, family_or_romantic_relationships, ideological_or_moral_commitments, curiosity_or_epistemic_drive, ambition_status_or_power, guilt_shame_or_desire_for_atonement).
- **AGENT_MOT_014 — Complexity of protagonist motivation**: How complex are the protagonist's motives across the story? (ordinal; responses: single, relatively stable goal or desire dominates, multiple but largely compatible goals or desires, conflicted or ambivalent motives are central (the protagonist is pulled in opposing directions)).
- **AGENT_MOT_016 — Dominant type of protagonist change**: If there is an internal character arc, what kind of change is most prominent? (categorical; responses: no substantial change / static character, moral or ethical shift (e.g., values, sense of right/wrong), psychological self-understanding (e.g., insight into self, trauma, desires), relational role shift (e.g., from outsider to insider, dependent to caregiver), status or power change (e.g., social rank, professional role, authority), ontological or metaphysical transformation (e.g., becoming non-human, godlike, or altered in reality-status)).

### Archetypes & Tropes

- **AGENT_TRP_001 — Explicit use of trope or archetype labels**: Does the narration explicitly refer to characters using trope or archetype labels (e.g., 'paladin', 'final girl', 'mentor', 'dragonish tycoon'), rather than only implying them? (binary; responses: yes, no).
- **AGENT_TRP_002 — Archetypal register of the central character**: In terms of how they are constructed, what register best describes the central character? (categorical; responses: mostly mimetic/realist individual (everyday realism), genre archetype (detective, cowboy, vampire, etc.), mythic or legendary figure (hero, trickster, godlike), allegorical or personified abstraction (e.g., land, institution, concept)).
- **AGENT_TRP_003 — Subversion or reinforcement of archetype**: Relative to the expectations of the archetype they evoke, does the story primarily reinforce, complicate, or subvert the central character's type? (categorical; responses: straightforward reinforcement of familiar archetype, partial complication/nuancing of archetype, overt subversion or inversion of expected role).
- **AGENT_TRP_005 — Degree of personifying institutions or systems as characters**: To what extent does the narrative treat institutions or large-scale systems (e.g., the Church, the Consortium, the law, the land) as if they were characters with motives and agency? (ordinal; responses: not personified, occasionally personified, consistently treated as agents).
- **AGENT_TRP_014 — Stance toward genre archetypes**: Does the storyworld tend to play genre archetypes straight, mix them with subversions, or mostly undermine them? (categorical; responses: mostly_plays_archetypes_straight, mix_of_straight_and_subverted, mostly_subverts_or_critiques_archetypes).

### Agency Distribution & Character Roles

- **AGENT_ROLE_015 — Configuration of primary plot-driving agents**: What is the typical configuration of the agents who primarily drive the plot? (categorical; responses: single_central_protagonist, dual_protagonists_or_pair, ensemble_multiple_equally_central, primarily_system_or_collective_agent).
- **AGENT_ROLE_016 — Agency of secondary characters**: How much independent agency do secondary/supporting characters have in influencing major plot developments? (ordinal; responses: minimal_mostly_reactive_helpers_or_obstacles, moderate_some_independent_initiatives, high_secondary_characters_regularly_drive_major_turns).
- **AGENT_ROLE_017 — Nature of antagonistic force**: What kind of antagonistic force most often opposes the protagonist? (categorical; responses: no_clear_antagonist, impersonal_force_or_collective_antagonist, singular_antagonist_with_little_interiority, singular_antagonist_with_substantial_interiority).
- **AGENT_ROLE_018 — Complexity of modeled social network**: How complex is the social network of relationships modeled between characters? (ordinal; responses: very_simple_few_relationships, moderate_web_of_family_friends_colleagues, dense_network_with_named_links_and_roles).

### Social and Intergenerational Dynamics

- **AGENT_ATTR_019 — Intergenerational relationships as core engine**: Do intergenerational relationships (parent–child, grandparent–grandchild, mentor–protégé across age gaps) consistently serve as core engines of character conflict and change? (binary; responses: no, yes).

### Character Transformation & Arc

- **AGENT_ATTR_021 — Dominant trajectories of main character change**: Which trajectories of change most commonly describe the main character's arc? (multi_select; responses: moral_learning_or_increased_empathy, trauma_and_partial_recovery, empowerment_or_gaining_agency, disillusionment_or_loss_of_idealism, corruption_or_moral_decline).

### Meta-Characters, Narratorial Voice & Figurative Characterization

- **AGENT_ATTR_024 — Density of figurative language in character depiction**: On a 1–5 scale, how dense is the use of figurative language (metaphors, similes, symbolic images) specifically in describing characters and their inner states? (scale; responses: 1, 2, 3, 4, 5).
- **AGENT_ID_022 — Presence of meta- or non-diegetic agents**: Do stories feature meta- or non-diegetic agents such as AI assistants, narrators, or conceptual entities that openly comment on their own fictionality or on the storytelling process? (binary; responses: no, yes).

### Interiority and Point of View

- **AGENT_ATTR_010 — Dominant technique for rendering interiority**: What is the main stylistic technique used to convey characters' inner life? (categorical; responses: first-person narration (the protagonist narrates their own thoughts directly), close or free indirect third-person (narrator's voice blends with a character's thoughts), explicit internal monologue marked as such (e.g., italics or quoted thoughts), reported thought summaries by an external narrator ('she realized', 'he felt that'), no direct interiority; inner states only inferred from behavior and dialogue).
- **AGENT_ID_024 — Number of distinct internal POVs**: How many different characters' inner thoughts or feelings does the narration directly enter (with interiority, not just reported speech)? (categorical; responses: zero (fully external or objective narration), one POV character, two POV characters, three or more POV characters).

### Archetypes and Tropes

- **AGENT_TRP_018 — Reliance on genre archetypes for main characters**: To what degree do the main characters conform strongly to recognizable genre archetypes (e.g., hardboiled detective, chosen one, femme fatale) without substantial subversion? (categorical; responses: low: protagonists are idiosyncratic and resist clear genre archetypes, medium: protagonists clearly echo genre archetypes but also complicate or subvert them, high: protagonists are strongly archetypal and largely follow expected genre patterns).

### Agency Distribution and Initiative

- **AGENT_ROLE_019 — Primary locus of plot-driving agency**: Where does most plot-driving agency reside: in a single human, multiple humans, or in non-human/systemic forces? (categorical; responses: single human protagonist mainly drives events, shared among multiple human characters (ensemble agency), non-human or system-level forces dominate (institutions, magic systems, AIs, environments), balanced mix of human and non-human agencies).
- **AGENT_ROLE_020 — Protagonist initiative vs. reactivity**: Is the protagonist mostly initiating key actions or mostly reacting to events imposed by others/forces? (ordinal; responses: mostly reactive to external events, mixed balance of initiative and reactivity, mostly initiates key actions and decisions).

### Relational Networks and Conflict Configuration

- **AGENT_ID_023 — Prominence of collectives as agents**: Are collective entities (e.g., 'the villagers', 'the Church', 'the Consortium') treated as major actors in the story, beyond background mention? (categorical; responses: absent or negligible (collectives not personified), present but background (collectives mentioned but rarely act as unified agents), foregrounded as major agents influencing or driving events).
- **AGENT_ROLE_021 — Social network richness around the protagonist**: How rich and varied is the protagonist's social network as portrayed in the story? (ordinal; responses: minimal: few close relationships shown (1–2 recurring connections), moderate: a small but varied set of relationships (3–5 recurring connections), dense: many distinct recurring relationships across family, peers, institutions (6 or more)).

### Emotional Modeling

- **AGENT_EMO_001 — Frequency of explicit emotion naming**: How often does the narration explicitly name the central character's emotions (e.g., 'she was afraid', 'he felt ashamed')? (ordinal; responses: rare/never, occasional, frequent).
- **AGENT_EMO_002 — Modes of conveying the central character's emotions**: Through which modes are the central character's emotions mainly conveyed? (multi_select; responses: explicit emotion words/labels, bodily sensations or physiology (e.g., heartbeat, nausea, trembling), metaphorical or environmental imagery reflecting mood, actions and choices as emotional indicators, dialogue content or tone revealing emotion).
- **AGENT_EMO_003 — Complexity of emotional arc**: How complex is the central character's emotional journey across the story? (ordinal; responses: largely single-tone, some distinct shifts, multi-phase or conflicted).
- **AGENT_EMO_004 — Presence of explicit emotional self-reflection**: Does the central character explicitly reflect on or analyze their own emotional state (e.g., 'I realized I was jealous', 'she wondered why she felt so calm')? (binary; responses: yes, no).


## Social Networks

Relationships: types, dynamics, power structures, and social topology in the story's world.

### Scope and Topology of the Network

- **SOC_STR_001 — Size of Social Network**: How many socially significant characters or entities (including key institutions treated as characters) does the story develop? (ordinal; responses: very_small_1_2_significant_nodes, small_3_4, medium_5_7, large_8_12, ensemble_13_or_more).
- **SOC_STR_010 — Individualization of Community**: How are broader communities (villages, crowds, congregations, online publics) represented socially? (categorical; responses: mostly_individualized_side_characters, mix_of_named_individuals_and_collective_masses, mostly_anonymous_crowds_or_collectives).
- **SOC_STR_017 — Dyadic vs Group Scene Emphasis**: To what extent do key social interactions occur in intimate dyads versus larger group scenes? (scale; responses: 1, 2, 3, 4, 5).

### Network Scale and Topology

- **SOC_STR_002 — Network Density of Side-to-Side Ties**: How densely connected are characters to one another beyond a single central figure? (categorical; responses: hub_and_spoke, moderately_interconnected, multi_clique_or_mesh).

### Network Topology & Scope

- **SOC_STR_003 — Institutions as Social Actors**: Do institutions or collectives (e.g., churches, governments, corporations, mobs, species, AIs) function as named social actors with relationships to characters? (binary; responses: no: institutions are absent or pure backdrop, yes: at least one institution/collective is personified as having ties, goals, or conflicts).
- **SOC_STR_004 — Community Salience**: How salient is the broader community beyond the central characters? (categorical; responses: none: no community or group beyond 1–2 characters is shown, background: a community exists but is mostly atmospheric (gossip, crowds) without driving events, active secondary agent: community exerts pressure, offers help, or significantly shapes outcomes, collective protagonist/antagonist: a group's fate or coordinated action is the main narrative focus).
- **SOC_STR_005 — Cross-Boundary Relationships**: Are there significant relationships that cross strong social boundaries (class, ethnicity, species, institution, ideology)? (binary; responses: no: all meaningful ties are within a single social stratum or kind, yes: at least one central relationship bridges clearly marked social boundaries).

### Representation and Medium of Relationships

- **SOC_REL_004 — Explicit Enumeration vs Enacted Interaction**: Are relationships mainly described through list-like summaries and labels, or through dramatized scene interactions? (categorical; responses: predominantly_enumerated_or_summarized, mixed_enumerated_and_scenic, predominantly_enacted_in_scenes).
- **SOC_REL_013 — Diversity of Communication Channels**: Through which channels do socially important communications between characters occur? (multi_select; responses: face_to_face_dialogue, letters_notes_or_diaries, digital_or_broadcast_media, ritual_or_ceremonial_actions, telepathic_or_supernatural_contact, indirect_via_objects_spaces_or_environment).
- **SOC_REL_016 — Reliance on Relationship Labels vs Inference**: Does the text explicitly label relationship types (e.g., 'uncle', 'boss', 'best friend'), or are they mostly inferred from behavior? (ordinal; responses: mostly_labeled_by_role_or_kin_term, mixed_labeled_and_inferred, mostly_inferred_from_behavior).

### Relationship Rendering and Exposition

- **SOC_REL_005 — Depth of Relational History Provided**: How much shared history between key characters is explicitly provided? (ordinal; responses: none_or_minimal, brief_glimpses, moderate_shared_history, extensive_lifelong_or_multi_phase_history).

### Content and Types of Relationships

- **SOC_REL_006 — Centrality of Non-Human or Technological Relationships**: How central are relationships between humans and non-human entities (ships, AIs, gods, monsters, magical artifacts) to the social world? (ordinal; responses: none_or_background_only, important_but_not_central, primary_axis_of_story).
- **SOC_REL_014 — Ontological Layers of Social Relations**: Beyond ordinary human-to-human ties, what other ontological layers of relationship does the story include? (multi_select; responses: human_to_supernatural_or_mythic_beings, human_to_AI_or_software_systems, human_to_personified_institutions_or_bureaucracies, human_to_simulations_games_or_time_loops, explicit_meta_relationship_to_narrator_reader_or_story_system).

### Relationship Types and Non-Human Partners

- **SOC_REL_007 — Range of Relationship Types Present**: Which distinct types of social relationships are meaningfully present in the story? (multi_select; responses: familial_kinship, romantic_or_sexual, friendship_or_peer, professional_or_economic, mentorship_or_teaching, adversarial_or_criminal, communal_or_neighborly, spiritual_or_supernatural).
- **SOC_REL_009 — Prominence of Non-Human or Institutional Relationship Partners**: To what extent are non-human entities (e.g., AI, gods, ships, land, corporations) treated as full relationship partners for characters? (ordinal; responses: none, peripheral_flavor, central_to_core_relationships).

### Relationship Types & Rendering

- **SOC_REL_008 — Show vs Tell in Relationship Construction**: To what extent are key relationships established through dramatized interaction versus explicit exposition? (scale; responses: 1, 2, 3, 4, 5).
- **SOC_REL_010 — Network Description Style**: How explicitly does the narration describe the social network (who is related to whom and how)? (categorical; responses: analytic-enumerative: relationships are explicitly labeled or listed (e.g., 'X is Y's mentor and Z's cousin'), scene-implied: relationships are inferred from scenes and dialogue without explicit listing or labeling, mixed: some explicit enumeration coexists with substantial scene-based implicit network building).

### Power Structures and Hierarchy

- **SOC_DYN_010 — Dominant Power Structure Form**: What kind of power structure most strongly shapes the social world of the story? (categorical; responses: egalitarian_peers, vertical_hierarchy, diffuse_systemic_power, shifting_or_contested).
- **SOC_DYN_012 — Centrality of Abusive or Manipulative Asymmetric Ties**: Is abuse, exploitation, or manipulation within an unequal relationship one of the central engines of the narrative? (binary; responses: yes, no).
- **SOC_PWR_015 — Attitude Toward Authority Structures**: What overall stance does the narrative take toward prevailing authorities or hierarchies (political, religious, corporate, familial)? (categorical; responses: legitimizing: authority is largely portrayed as justified, wise, or protective, ambivalent/mixed: authority has both protective and harmful aspects; critique and respect coexist, critical: authority is shown as corrupt, unjust, or harmful, with little endorsement, subversive: protagonists consciously work to undermine, escape, or overturn authority structures).
- **SOC_PWR_016 — Presence of Broker/Bridge Characters**: Is there at least one character whose primary narrative function is to mediate between otherwise separate groups, classes, or worlds? (binary; responses: no: no clear bridging figure; groups relate directly or not at all, yes: a distinct mediator (translator, negotiator, go-between, anchor, emissary) stands between groups).

### Social Change, Conflict & Transformation

- **SOC_DYN_011 — Central Relationship Trajectory**: What best describes the main trajectory of the most central relationship or small cluster of relationships? (categorical; responses: formation: a new bond is created or strangers become tied, strengthening/repair: an existing strained or modest bond deepens or is healed, deterioration/betrayal: trust erodes, affection cools, or exploitation emerges, breakup/separation/death: a bond ends decisively through departure, rupture, or death, stable: the relationship's nature is largely unchanged by the story's end, cyclical/on-off: the relationship oscillates between connection and distance without net resolution).

### Social Change and Relationship Arcs

- **SOC_DYN_013 — Primary Trajectory of Central Relationship(s)**: What is the dominant trajectory of the central relationship or relationships over the course of the story? (categorical; responses: relationship_formation, strengthening_or_reconciliation, testing_but_survives, breakdown_or_betrayal, repetitive_pattern_no_clear_change, arc_ambiguous_or_fragmentary).
- **SOC_DYN_014 — Number of Major Relationship Turning Points**: How many distinct major turning points occur in the central relationship arc(s)? (ordinal; responses: zero, one, two, three_or_more).

### Community Presence and Crowd Dynamics

- **SOC_STR_016 — Salience of Broader Community Beyond Core Characters**: How salient is a broader community or social milieu beyond the central characters? (ordinal; responses: none, background_mentioned_only, supporting_minor_roles, community_as_active_collective_actor).
- **SOC_STR_018 — Crowds or Mobs as Coherent Agents**: Are crowds, mobs, or large groups personified and treated as coherent social agents within the story? (binary; responses: yes, no).

### Conflict Modality and Resolution

- **SOC_DYN_019 — Dominant Interpersonal Conflict Modality**: How does interpersonal conflict most often manifest between characters? (categorical; responses: open_confrontation, covert_manipulation_or_abuse, avoidance_or_silence, structural_or_institutional_conflict).
- **SOC_DYN_020 — Violence Within Close Relationships**: Does physical or severe psychological violence occur within close relationships (family, romantic partners, long-term mentors/guardians)? (binary; responses: yes, no).
- **SOC_DYN_021 — On-Page Reconciliation or Forgiveness**: Is there a depicted moment of reconciliation or forgiveness between previously conflicted parties? (categorical; responses: yes_substantial_reconciliation, partial_or_ambiguous, no_reconciliation).

### Communication Channels and Mediation

- **SOC_REL_022 — Primary Channel for Deep Relational Content**: Through which channel are the most important emotional truths or shifts between characters primarily conveyed? (categorical; responses: direct_spoken_dialogue, shared_actions_and_routines, written_or_recorded_media, internal_monologue_or_fantasy).
- **SOC_REL_023 — Presence of Ritualized or Coded Communication**: Do characters rely on ritual, formalized scripts, games, or specialized codes to communicate relational meanings? (binary; responses: yes, no).
- **SOC_REL_024 — Narrative Frame as Social Interaction**: Is the entire story presented as a social interaction between a narrator and an in-world listener (e.g., confession, testimony, letter to someone)? (binary; responses: yes, no).

### Communication Channels & Mediation

- **SOC_COM_017 — Dominant Channel for Pivotal Interactions**: Through what medium do the story's most pivotal relational moments (confessions, betrayals, reconciliations, decisions) primarily occur? (categorical; responses: face-to-face spoken dialogue, written or recorded media (letters, emails, case files, legal documents, logs, forum posts), ritual/action/gesture (shared labour, offerings, performances, nonverbal acts), mediated/technological (phone, video, simulations, AI interfaces, social apps), internal/imagined (dreams, fantasies, silent addresses to absent or dead others)).
- **SOC_COM_018 — Collective or Choral Voices**: Does the narrative employ collective or choral voices (e.g., villagers as 'we', gossip choruses, omniscient summarizing of a crowd's view) as a distinct social perspective? (binary; responses: no: narration and focalization stay with individuals only, yes: a group perspective or chorus is used to comment on or participate in events).

### Power Structures and Conflict Modalities

- **SOC_DYN_007 — Explicitness of Hierarchy and Authority**: How overtly does the story mark and use social hierarchies (ranks, chains of command, legal authority) in its relationships? (ordinal; responses: minimal_or_flat_relations, informal_or_implied_hierarchies, formalized_and_explicit_hierarchies).
- **SOC_REL_012 — Role of Gossip and Rumor**: Do gossip, rumor, or reputational narratives function as key mechanisms shaping relationships and outcomes? (binary; responses: salient_gossip_or_rumor_dynamics, minimal_or_no_gossip).
- **SOC_REL_018 — Power Symmetry in Central Relationship**: Is the central relationship in the story characterized by strong power imbalance or relative equality? (categorical; responses: strongly_asymmetric, moderately_asymmetric, largely_peer_like).

### Change, Transformation, and Temporal Extent

- **SOC_DYN_008 — Protagonist's Social Trajectory**: Over the course of the story, does the protagonist's core social world expand, contract, or remain essentially stable? (categorical; responses: network_expands_or_integrates, network_contracts_or_leads_to_isolation, largely_stable_core_network, ambiguous_or_unfinished_trajectory).
- **SOC_DYN_009 — Degree of Relationship Transformation**: How many major relationships undergo substantial qualitative change (e.g., enemy to ally, stranger to family, mentor to rival)? (ordinal; responses: none_or_trivial_shifts, one_major_transformation, multiple_major_transformations).

