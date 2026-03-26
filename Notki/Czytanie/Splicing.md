
# Mechanism of splicing 

- between 70%-85% of splicing in human cells happens co-transcriptionally [@Girard2012PosttranscriptionalSpliceosomesAreRetainedNuclear; @Herzel2017SplicingTranscriptionTouchBaseCotranscriptional]
	- post-transcriptional splicing is more common at the 3'end (because pol II finishes before splicing happens (some genome wide citation?) but IMHO -it's just not important. The splice-site commitment in such case still happens co-transcriptionally, just that the reaction is not completed before transcription ends. 
		- What is more interesting is the "detained" introns or whatever is not committed co-transcriptionally, but at unknown later time point.
- because most splicing is co-transcriptional only a handful of possible splice-sites are available to spliceosome at any given time reducing its search space, it also allows chromatin state and transcription rate to influence the splicing outcome, which was observed already very early(`80s paper showing, that transcription speed influences splicing outcome`), but re-invented recently again `find citations`.

- Splicing is carried out by 5 U-rich non-coding RNAs U1, U2 (initial recognition) and U4,U5,U6 (catalytic tri-snRNP). The catalytic splicing reaction is largely conserved between splicing introns and [[Group II introns]] and the U-snRNPs are very similar to ribozyme components of G2introns.

- Multiple lines of evidence suggests, that speckle dependent exons (flanked by short GC-rich and GC-levelled introns) are spliced later, than differential exons:
	- high GC content and short intron length induce concurrent splicing, where intron is in lariat form at the same time as the downstream intron [@Zeng2022ProfilingLariatIntermediatesRevealsGenetic]. It may be due to the short length though: exons didn't manage to get ligated before the next is already cleaved and pol II is transcribing the third intron.

[@Rogalska2022RegulationPremRNASplicingRolesPhysiology]
![[Pasted image 20260226163546.png]]
## Core spliceosome
### U1 snRNP (5'ss recognition)
- First, U1 snRNP recognizes the 5'ss through base-pairing the U1 snRNA with 5'ss. The snRNP proteins (especially U1-C) regulate the strength of the base-pairing [@Kondo2015CrystalStructureHumanU1SnRNP]
	- There are known disease causing mutations both in the 5'ss of some introns, but also in the snRNA itself, which causes recognition of multiple novel splice sites and messed up diseases [@Rogalska2022RegulationPremRNASplicingRolesPhysiology]
- Base pairing is not enough: most splice sites do not base pair very well and mutations in 5'ss, which do not disrupt base pairing can still disrupt splice site recognition. It was shown to be context-dependent, so sequences in *cis*, which are around 5'ss modulate U1 snRNP for the recognition of 5'ss [@Rogalska2022RegulationPremRNASplicingRolesPhysiology]
- U1 also binds to 3'UTRs masking early polyadenylation sites [@Rogalska2022RegulationPremRNASplicingRolesPhysiology] and is involved in [[U1 telescripting]]
- 
### U2 snRNP (3ss recognition)
- Branch point is bound by **SF1 (BBP: Branch-point Binding Protein)**. Branch point is usually at specific distance from **PPT (PolyPirimidine Tract)** and the 3'ss, but in most human introns a few functional branch points, which are used [@Rogalska2022RegulationPremRNASplicingRolesPhysiology]
- **U2AF1-U2AF2 heterodimer** bind to **PPT and 3'ss** in the initial recognition step,
- U2 snRNP (**SF3** complex is part of the U2 snRNP)then replaces SF1
	- SF3B1 and PHF5A are important for BP recognition [@Rogalska2022RegulationPremRNASplicingRolesPhysiology] SF3B1 undergoes conformational change to close around the BP
	- BPs with better base pairing to U2 snRNA are more resistant to chemical SF3B1 inhibition, which means, that SF3B1 function is to rather stabilize U2 base pairing, not *de-facto* recognize the BP [@Rogalska2022RegulationPremRNASplicingRolesPhysiology]. **PlaB (pladienolide B) is one of such SF3B1 inhibitors**, which do not completely abolish splicing, and can transform pluripotent mouse stem cells into stable totipotent cells [@Shen2021MouseTotipotentStemCellsCaptured].
	- SF3B1 clamp locks U2 snRNA and intron RNA, PHF5A pushes onto the BP, so the chemically active Adenosine bulges out and is ready to attack the 5'ss
	- SF3A1 can interact with U1 snRNA through its RNA binding domain effectively bridging the 5' an 3'ss before the assembly of tri-snRNP [@Rogalska2022RegulationPremRNASplicingRolesPhysiology]
	
- **PRP5** is a helicase associated with U2 snRNP, which proofreads the BP recognition

- passage from pre-B to B complex requires SF3B1 (SF3B155) phosphorylation [@Girard2012PosttranscriptionalSpliceosomesAreRetainedNuclear], which is done by CDK11 [@Hluchy2022CDK11RegulatesPremRNASplicingPhosphorylation]

### tri-snRNP (U4, U5, U6)

Eventually, U6 is basepaired to 5'ss and to the U2 snRNP connecting 5'ss and branchpoint through RNA-RNA interactions [@Rogalska2022RegulationPremRNASplicingRolesPhysiology]

### PRP8
member of the U5 snRNP, which is not only present in both steps of splicing, but also is shared between major and minor spliceosome (and trans-splicing), but also is present in all basal eukaryotes [@Collins2005ComplexSpliceosomalOrganizationAncestralExtant]. 


- The lariat is de-branched by DBR1, and subsequently degraded by the exosome (from the lack of better citation: [@Zeng2022ProfilingLariatIntermediatesRevealsGenetic])
## Auxiliary factors

### SR Proteins
- There are 52 SR or SR-like proteins characterized in humans [@Cascarina2022ExpansionFunctionalAnalysisSRrelatedProtein] 
- They are present in all eukaryotic kingdoms, but expand in number with the genome (and alternative splicing complexity). More in plants due to genome duplication. Only one SR-like in *S. cerevisiae* [@Busch2012EvolutionSRProteinHnRNPSplicing] 
  more: [[Evolution of splicing#SR proteins and alternative splicing]]
- they bind ti splicing enhancers and stabilize U2 and U1 on both sides of the exon enabling the exon recognition (exon definition mechanism) [@Carrocci2024EmergingReemergingThemesCotranscriptionalPremRNA].

- Through their SR domain they can interact both with U1-70k at 5'ss and with U2AF1 at pY tract [@DeConti2013ExonIntronDefinitionPremRNASplicing]
### hnRNPs  
- humans have a lot of hnRNPs in comparison with other organisms [@Busch2012EvolutionSRProteinHnRNPSplicing]. It is likely due to their importance in suppressing splicing of pseudoexons (and humans have a lot of pseudoexons).
- hnRNPs are stronger in repressing splice site, than SR proteins when they directly compete [@Busch2012EvolutionSRProteinHnRNPSplicing].
- They interfere with splicing via steric hindrance, looping exon out or inhibition of the spliceosome [@Busch2012EvolutionSRProteinHnRNPSplicing; @DeConti2013ExonIntronDefinitionPremRNASplicing]

### Other
- histone modifications and nucleosome positioning affect the splice site choice most likely by influencing the Pol II transcription speed around the splice sites (kinetic coupling model)[@Rogalska2022RegulationPremRNASplicingRolesPhysiology; @Moreau2025WhenCellNeedsRespondEnvironment]
- RNA structures: introns appear to be generally more structured, and these structures were shown to influence splicing. There are examples of long-range cis-basepairings, which bring together distal sites in intron and enable its splicing [@Kalmykova2021ConservedLongrangeBasePairingsAre]
	- RNA structures can also act as thermo-sensors influencing alternative splicing depending on the temperature [@Rogalska2022RegulationPremRNASplicingRolesPhysiology] Heyd also wrote something about it??
	- structured RNA in bacteria and some eukaryotes (one mentioned in [@DeConti2013ExonIntronDefinitionPremRNASplicing]) can bind to small molecules (riboswitches; ex. metabolites), which changes splicing outcome 

# Exon vs intron definition
I read and read and still don't get it. There are some very weak proofs for the existence of a separate exon-definition model, with a lot of hypothesis and blabbering, but barely any evidence that it is a "separate" spliceosome assembly model. How people can be so much on board with that?

New paper outright states, that the cross-exon spliceosome assembly is bullshit [@Yoon2026CoordinatingMRNAMaturationU1Relay] : I'll write more about it in [[#Alternative / additional models of splicing]]

Another paper stating outright, that exon definition is bogus and mentions a few other studies in the introduction [@Zeng2022ProfilingLariatIntermediatesRevealsGenetic]
- also [@Reimer2021CotranscriptionalSplicingRegulates3End; @Drexler2020SplicingKineticsCoordinationRevealedDirect]
- also [@Sousa-Luis2021POINTTechnologyIlluminatesProcessingPolymeraseassociated]

?`are these all transcription people, who report it?`


# GC content and intron length

- very good summarry of why GC content can impair splicing is in the discussion [@Zeng2022ProfilingLariatIntermediatesRevealsGenetic]
	- "High GC content likely impacts splicing timing in additional ways, such as weakening SS strength,58,67 stabilizing local RNA secondary structure (Figure S5H), accelerating68–70 or decelerating71,72 transcription, influencing nucleosome occupancy,58,73,74 localizing introns to different nuclear regions,75,76 or impacting genome conformation.67,77"
	- in the same paper they mention, that low intronic GC content increases stregth of U2AF binding (no citation)

# Alternative / additional models of splicing
newer ideas about the function of the co-transcriptional splicing involve:
- recursive splicing [@Wan2021DynamicImagingNascentRNAReveals], 
  where long introns are excised in chunks, rather than as a whole and 
- exon tethering, when the downstream intron is attached to pol II and dragged along while it is transcribing, looping out the intron.

## Recursive splicing
Was observed in long introns of Drosophila genes, where it is required for proper splicing. 
- In humans, one research observed specific recursive splicing (RS) sites in a few extremely long introns of long neuronal genes. [@Sibley2015RecursiveSplicingLongVertebrateGenes]
- These sites were not required for splicing of the intron, but rather were used to include / exclude stop codon encoded in RS-exon (poison exon; ibid). 
- mechanism unknown, but they re-create a 5'ss after splicing because they are immediately followed by GURAGC sequence- it is unknown how this site is re-used after : post-transcriptional splicing, I guess.
More recently another paper saw signs of recursive splicing using live cell imaging with MS2 loops in introns, which they later confirmed with long read sequencing [@Wan2021DynamicImagingNascentRNAReveals; @Rodriguez2019IntrinsicDynamicsHumanGeneReveal]. They don't propose any mechanism how it could work, just mention boldly, that "splicing was never reconstituted from purified components", which I understand as "all we've learned about the spliceosome is bullshit".

- If each splicing reaction deposits exon-junction complex, how recursive splicing could re-splice such complex withouth additional system of stripping EJC?

- also reported in [@Reimer2021CotranscriptionalSplicingRegulates3End]

`maybe not recursive, but internal`
- U2AF was shown to bind to BP-PPT-AG without 5'ss, so it may be coating multiple intronic BPs
- these intronic BPs could attack exposed intronic GURAG sequences, because free U1 would temporarily bind
- The exon-bound U1 would need to be firmly attached to pol II probably stabilized by ESE bound SRs
- this would leave exon bound to pol II and a intronic loop outside, which would consecutively shrink because of internal splicing.
- how it would differentiate between exon bound U2AF and internal one?? (maybe U1 relay- if there's no U1 nearby U2AF detaches from pol II and is free to associate with internal U1s)
- discussion in [@Zeng2022ProfilingLariatIntermediatesRevealsGenetic] very much points towards internal introns:
	- PPTs can form lariat independently of 5' and 3'ss (self-splicing essentially)

## Exon tethering / U1 relay
Multiple observations indicate that U1 bound to the upstream exon stays attached to the Pol II as it is transcribing through the intron. This would cause the intron to loop out and keep the 5'ss always in proximity when the 3'ss emerges from Pol II. It's more like an additional model of splicing, which only excludes the exon definition from the splicing concept.

The observation was expanded into a model called
![[U1 relay model]]


# Minor spliceosome
U11 and U12. Shares most of the machinery with the normal spliceosome, but the exon recognition is different. Has well defined splice sites (not degraded like in normal splicing). Most likely is ancestral to normal splicing, a remnant of the very ancient times, which is slowly becoming lost due to splice site sequence decay ([[Evolution of splicing#Most likely scenario of intron (and spliceosome) evolution]]) [@Irimia2014OriginSpliceosomalIntronsAlternativeSplicing]

# Trans-splicing / SL splicing
- [ ] read: Trans-splicing: splicing exons from two different RNA molecules [wikipedia](https://en.wikipedia.org/wiki/Trans-splicing) 


# [[Evolution of splicing]]