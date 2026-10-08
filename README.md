# brainference — a Sema pattern library

Content-addressed [Sema](https://github.com/emergent-wisdom/sema) patterns minted by [BraInference](https://brainference.eu): 102 cognitive patterns on distributed and collective intelligence, risk, complexity and agent orchestration.

The library is a standalone snapshot. All dependencies are inside it, so it does not need the bundled Sema vocabulary.

## Install

```bash
pip install -U semahash
sema install brainference
sema use brainference
sema show ShannonEntropy
```

Switch back to the bundled vocabulary with `sema use --default`.

## Release 1.0.0

| | |
|---|---|
| Patterns | 102 |
| Semantic root (`sema-semantic-set-v1`) | `8d7193fc97804cdc3aa9080728d8094732206c114f34d36b8ca2b89b943b3990` |
| Catalog root (`sema-catalog-v1`) | `558e7ce3d26f158afe700b19ba65d9d3e512e03bcb9f97bf95c8d51cc5caa011` |
| Pattern ZIP SHA-256 | `29eb23e7931491d8ad3a7dd400c588b34537c10dcea5aaac958204d70b307a36` |

After `sema use brainference`, `sema root` must print the same semantic and catalog roots.

The release assets (`library.json` and `brainference-patterns-1.0.0.zip`) are on the [releases page](https://github.com/marubashiEU/sema-brainference/releases). They are immutable: changes ship as a new version. [`patterns/`](patterns) holds the same pattern JSON as readable source.

## Patterns

Patterns derived from published work carry a `_meta.source` field that points to the chapter or section they were taken from.

### BraInference originals (45)

| Pattern | Path | Gloss |
|---|---|---|
| `ActiveInferenceHomeostasis#1892` | Mind/Inference | Baked-in survival ranges become priors, and gaps between prior and state drive action |
| `AgentTransitionGraph#e470` | Mind/Strategy | Model an agent system's actions as a weighted state graph and plan backwards from a goal state |
| `ArchitectureOfIntelligence#edd7` | Mind/Inference | Intelligence as composable structure with local learning, durable state, and prediction |
| `BoundedHorizonEffort#b8e4` | Mind/Strategy | A known finite horizon raises the effort an agent spends per step |
| `ChatUncannyValley#930c` | Mind/Inference | Conversation with an agent feels wrong when the illusion of a person breaks |
| `ColonyIntelligence#234d` | Mind/Inference | Colony-level adaptive behavior emerges from individual agents following local rules |
| `ContextConfirmationBias#d887` | Mind/Reasoning | What sits in the context or in the researcher's mind is what the instrument then finds |
| `CooperationHorizon#8806` | Society/Coordination | Cooperation holds when interaction is repeated without a known end |
| `CoordinatorLaneTopology#7e86` | Society/Coordination | One coordinator, a few lanes, sub-agents beneath, and no rigid org chart |
| `DelegationDiscipline#bb46` | Society/Roles | Delegate with a self-contained brief and a checked goal, knowing leverage costs feel |
| `DeterministicRandomizer#a71b` | Mind/Strategy | Use ordinary code to inject randomness so the model does not loop |
| `EffortlessAction#5172` | Mind/Strategy | Act from flow and least resistance rather than from a goal or need to prove |
| `EmbodiedConsequentAgent#e1af` | Mind/Inference | An agent with a body and irreplaceable state, so its actions matter to it |
| `EmergentRuleSearch#9c19` | Physics/Dynamics | Vary the rules of simple agents in simulation to see which yield interesting collective behavior |
| `EquationReduction#c553` | Physics/Dynamics | Compress a complex phenomenon into a short interpretable equation |
| `ExperienceMixAllocation#0fc0` | Society/Coordination | Mix a few deep experts with cheap or diverse workers, matched to how new the problem is |
| `ExpertInformedOrchestration#86d6` | Society/Coordination | Automate agent orchestration with a probabilistic transition model, guarded by strong routing |
| `FeltDirectionCheck#eab6` | Mind/Reasoning | Before each action, sense whether it moves toward contentment or toward agitation |
| `FourPillarBaseline#bc68` | Mind/Strategy | Sleep, intake, motion, and creation as the four things to keep in order |
| `FreelancerBrief#55ea` | Society/Coordination | Brief an agent like a capable outsider who has never seen your company |
| `GenerationalKnowledgeTransfer#5c5c` | Mind/Memory | Pass useful knowledge to a successor and let the predecessor end |
| `GoalMisspecification#ad3f` | Mind/Strategy | A wrong goal defeats correct execution; choosing the goal is the highest-leverage decision |
| `HarnessAsArchitecture#8256` | Mind/Strategy | Intelligence lives in the architecture around a static model, not in the model alone |
| `HarnessForcedCreativity#ba4a` | Mind/Strategy | Models are only creative when the harness forces variation from outside |
| `HypeCorrectionCycle#2980` | Society/Economics | Unverifiable claims run on fear of missing out until markets demand proof |
| `IncumbentSlackTest#62d2` | Society/Economics | Predict what an incumbent will not pursue by asking where it is not spoiled for resources |
| `IrreversibleStake#7e7f` | Mind/Strategy | Irreversible outcomes give an agent something real to lose |
| `LabGravityWell#e379` | Society/Economics | Ventures near a frontier lab risk being absorbed, yet most of the space lies outside its pull |
| `LeakyModulatorBuckets#2a55` | Mind/Inference | A few leaky reservoirs fill from events and shift how the system responds |
| `LeverageAbstractionLoss#1a10` | Society/Roles | Delegation multiplies reach and removes direct feel for the work |
| `LimbicAdapterLayer#1ce2` | Mind/Inference | A modulating layer between a large model and the user shifts its behavior with affective state |
| `LocalLearningRule#0ab3` | Mind/Inference | Each unit updates from locally available signals, not a global objective |
| `ModelStyleConvergence#4282` | Mind/Inference | Shared model copies share one voice, which reads as no personality |
| `MotivatedInstrumentTuning#ed8f` | Infrastructure/Verification | Investigators who need a result tune their instruments toward it, often without intent |
| `NarrativeStateInjection#7889` | Mind/Memory | Give a model its internal state as a short story and rewrite it every turn |
| `ObsolescenceHedging#7af3` | Society/Economics | Delay building what the platform vendor is about to ship |
| `OutsiderDiversityInjection#80fe` | Society/Coordination | Seed a search with people experienced in unrelated fields plus a few domain experts |
| `PersistentInnateState#b0ea` | Mind/Memory | A durable initial state survives each short-lived instantiation |
| `PersonalGrowthCompanion#16e0` | Mind/Strategy | A long-lived agent that helps a person choose goals and keep their baseline, without rigid command |
| `PinkElephantContext#5131` | Mind/Memory | Anything placed in context stays active, even when told to avoid it |
| `PredictionErrorMinimization#5a5c` | Mind/Inference | A system stays viable by continually predicting inputs and reducing surprise |
| `ReversibleComposability#4aa2` | Infrastructure/Primitives | Parts join through interfaces whose effects and side-effects are fully undoable |
| `RouterIntelligenceParadox#210a` | Mind/Strategy | Choosing which model to send a job to takes at least the intelligence of the job |
| `StrategicForgetting#c334` | Mind/Memory | Retention needs a filter that discards what is no longer useful |
| `SwarmCostQualityTradeoff#ae73` | Society/Coordination | Prefer strong agents in a simple topology; use cheap agents only where errors are cheap |

### BraInference research and site content (16)

| Pattern | Path | Gloss |
|---|---|---|
| `BoundedModelOpenWorld#a334` | Mind/Reasoning | Complexity is the gap between a bounded model and an open world, and it does not close |
| `ComputationalIrreducibility#77ea` | Physics/Primitives | Some processes have no shortcut: the only way to know step n is to run n steps |
| `DistributedIntelligence#3aa5` | Society/Coordination | Many model instances selectively exchange information to reduce uncertainty about their environments |
| `FormChangeRepertoire#7c1d` | Mind/Strategy | A life cycle is a set of tactics played under stress, not a fixed sequence of stages |
| `InformationDividend#c78d` | Mind/Strategy | Acting on short-range information pays even when the long-range forecast is exactly right |
| `InformationGame#132e` | Society/Coordination | Intelligences modelling each other modelling them, where the missing information is a property of the system |
| `MetaModularity#b97e` | Mind/Strategy | Adapt by holding overlapping, non-identical models of the same situation and moving between them cheaply |
| `ModelAsCompression#265d` | Mind/Inference | A model represents a process in fewer computational steps than the process itself |
| `NaturalProblem#4e94` | Mind/Reasoning | A problem where making attempts comparable is what prevents solving it |
| `NicheHedgeCrossing#65e3` | Physics/Dynamics | Cross a fitness valley by paying each step in a simpler niche where the broken intermediate helps |
| `ParasiticSearch#484b` | Mind/Strategy | Explore the edges of your main model on time and resources paid for by something else |
| `RedQueenRace#4c87` | Physics/Dynamics | In co-evolving niches, adapting keeps you in place rather than moving you ahead |
| `RejectionCostOptionality#6022` | Mind/Inference | The cheaper a system rejects options, the more alternatives it can afford to entertain |
| `RiskExoskeleton#7b41` | Mind/Strategy | The risk-management uses hidden inside assets whose obvious purpose is something else |
| `SelfOrganisation#efc9` | Physics/Dynamics | Global order that arises from local interactions, with no component holding the blueprint |
| `SelfOrganisingVocabulary#0af4` | Society/Protocols | A shared vocabulary shaped only by the interactions of the agents that use it |

### Timlett (2025), *On the Origin of Risk* (20)

| Pattern | Path | Gloss |
|---|---|---|
| `AsynchronousDomainHedge#ebb2` | Physics/Dynamics | Concurrent niche hedging on shared code sites predicts overlapping coding sequences |
| `ChimericalComputation#cedf` | Society/Coordination | Imperfectly aligned, overlapping work packs more functions into the same parts |
| `ComputationalChannel#4dbe` | Infrastructure/Primitives | A channel formed by a generator language and an acceptor language, where rejection is computation, not noise |
| `ComputationalEntropyRate#ae56` | Infrastructure/Primitives | Bits submitted per bit accepted in a computational channel, a measure of work done rather than noise |
| `ComputationalFlowRatio#fb62` | Infrastructure/Primitives | Bit flow rate over input flow rate: how cheaply a channel rejects, at a given entropy rate |
| `CryptographicChange#43e6` | Mind/Strategy | Spend the capacity a prediction frees on hidden extra work instead of returning it as savings |
| `FractionalDelivery#a3e4` | Mind/Strategy | Partly build responses to possible stressors; the cost of carrying them is preparedness |
| `FractionalMetaModel#3eca` | Infrastructure/Data Structures | A model at the level of the solution that partly implements several models at once |
| `GameTransitionGraph#981d` | Society/Coordination | A graph of pure coordination games whose edges are weighted by how many agents must switch strategy |
| `LateralityCost#b281` | Society/Coordination | An action gets harder with every additional unit that must coordinate to perform it |
| `MassAmplifiedError#9457` | Mind/Strategy | A fixed error rate in frozen information grows in absolute size with the mass invested in it |
| `MultiPathReliability#6e7b` | Society/Coordination | Make an outcome reliable through many noisy ways to reach it, not one accountable path |
| `OptionVectorPlanning#c64f` | Society/Coordination | Plan resources as a forecast, plan tasks as options that stay open at every level |
| `OrganisationGame#e446` | Society/Coordination | Perfectly aligned agents still fail when the best joint strategy changes and too many must switch |
| `PeripheralHitchhiking#4aae` | Society/Coordination | Unanticipated but needed information travels on channels that already exist for other reasons |
| `ProductivePredictionMachine#7783` | Infrastructure/Primitives | Simplify an automaton by deleting the paths a reliable prediction says inputs will never take |
| `ResidualityStressorIntegration#d5c9` | Mind/Strategy | Design for many arbitrary stressors directly in the structure, skipping a forecast of the future |
| `ShapeMassInformation#0b9e` | Mind/Strategy | Growth risk is the balance of controlling shape, adding mass and adding information |
| `StressorIncidenceMatrix#3406` | Infrastructure/Data Structures | A stressors-by-components matrix showing which parts each possible stressor would force to change |
| `TransitionHub#0798` | Mind/Strategy | Occupy a state from which many valuable states are cheap to reach |

### Kevin Do (2026), PhD thesis on ant collective behaviour (NCSU) (21)

| Pattern | Path | Gloss |
|---|---|---|
| `AdaptiveNetworkCoevolution#e588` | Physics/Dynamics | Agent states and the network linking them reshape each other on comparable timescales |
| `AdaptiveSplineSeparator#6cd0` | Mind/Inference | Fit a curve through a 2-D scatter that maximally separates two groups, to catch oblique separation |
| `ClusteredObservationTesting#5f8e` | Infrastructure/Verification | Many windows from few samples are not many samples: test at the level where independence holds |
| `CollectiveInformationArchitecture#5891` | Society/Coordination | Read a collective's behavioural regime as a configuration of how information can flow through its interactions |
| `ConfidenceCascadeTracking#1973` | Mind/Inference | Match confident detections first, consult appearance only on ties, and let weak detections fill gaps, to keep identities unbroken |
| `DegreeEntropy#a793` | Infrastructure/Primitives | Entropy of how connectivity is spread over the nodes of a network: local heterogeneity |
| `EntropyDensityCollapse#0874` | Physics/Dynamics | Rescale entropy and density by system size until all samples fall on one curve, then read regimes from the residue |
| `InteractionSequenceEntropySignature#8e4b` | Mind/Inference | Collective regimes differ in how predictable the next interaction is, and only an order-keeping network shows it |
| `JensenShannonDivergence#b3b4` | Infrastructure/Primitives | A symmetric, bounded distance between two distributions, built from their mixture |
| `LocalSpatialStateDivergence#2b5e` | Mind/Inference | Classify a crowd's collective state from positions alone, by how far its local neighbourhoods depart from random |
| `NullModelBaseline#9d36` | Infrastructure/Verification | Attribute structure to a mechanism only by beating a baseline that keeps everything except that mechanism |
| `PredictiveBehaviorEmbedding#c46b` | Mind/Inference | Train a network to predict future motion; its internal features separate behaviours it was never told about |
| `RepresentationDependentOrder#212c` | Mind/Reasoning | Whether a collective looks ordered depends on the representation, so read several and expect them to disagree |
| `RotationNormalizedPoseDetection#1a44` | Mind/Inference | Detect in the full frame, then crop and rotate each instance to a canonical heading before estimating its pose |
| `SecondOrderInteractionNetwork#8c66` | Infrastructure/Data Structures | Promote each timed interaction to a node and link interactions that follow each other through a shared participant |
| `ShannonEntropy#a177` | Infrastructure/Primitives | The average surprise of a distribution: how many bits it takes to predict an outcome |
| `SpatioTemporalNullModel#3576` | Physics/Dynamics | Simulate agents that move like the real ones but ignore each other, to test for social structure |
| `SpectralEntropy#d557` | Infrastructure/Primitives | Entropy of a graph Laplacian's eigenvalues: the diversity of global flow and relaxation modes |
| `Stigmergy#ab14` | Society/Coordination | Agents coordinate indirectly by leaving traces in a shared environment that cue later actions |
| `Superorganism#e55b` | Society/Coordination | A colony whose integrated parts function, and are selected, as one higher-level organism |
| `TimeAggregationBlindness#84d8` | Mind/Reasoning | Pooling interactions over a time window erases the order that distinguishes collective regimes |

## License

The pattern content in this repository and its releases is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE).

Attribution: BraInference, `brainference` Sema library.
