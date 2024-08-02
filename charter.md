# Non-Terrestrial Networking Research Group (NTNRG)

The Non-Terrestrial Networking Research Group (NTNRG) is chartered to
explore and investigate research questions related to architectural, protocol design,
manageability considerations, and approaches to operationalize non-terrestrial networks.
Specifically, NTNRG focuses on networking
among nodes with highly dynamic connectivity imposed by virtue of their
non-terrestrial deployment environment. This includes High Altitude Platforms
(HAPS), typically in the stratosphere, satellites in Low, Medium, and
Geostationary orbits (LEO, MEO, GEO), and platforms in other cislunar
trajectories.

Previous IRTF work (DTNRG) focused on the delay and disruption tolerance
required to communicate effectively in extreme connectivity-challenged
scenarios (vis. RFC 4838). That effort has led to the creation of the IETF DTNWG which
standardized BPv7 (RFC 9171) and BPSec (RFC 9172).
Since then, network nodes on aerospace platforms in the cislunar regime
have seen a rapid rise in deployment and scale. This regime poses less extreme
time constraints on connectivity, but the rapidity of change and variability
of topologies that might be built among nodes moving through this environment
present new challenges.

The intended work products of the NTNRG include evaluation of the impact to
inter-networking among NTN nodes imposed by these deployments as well as
possible mitigation of adverse effects. Of specific
interest are:

  * simulation, measurement, or testing techniques that are particularly
    well suited for NTNs,
  * analysis of any impact to transport protocols as paths experience normal
    changes in characteristics like latency, jitter, and loss associated with
    nominal platform behavior,
  * investigations of the challenges and benefits of tuning existing
    transport and application protocols in emerging NTN architectures, and
  * exploration of management approaches that take into account NTN-specifics. 

NTNRG may also consider the implications of and requirements for NTN nodes
from different administrative domains dynamically providing connectivity.
The control plane requirements and trust model design parameters are
especially relevant.

An explicit non-goal is to propose changes to existing IETF protocols.
The research group may explore ideas that require such changes, and is uniquely
placed to discuss their implications with the IETF community, but the potential
incorporation of such ideas into the standards process is a matter for the IETF
and is out of scope for this group.

Considerations related to hosts connecting to an NTN and path selection strategies
among available connectivity (including via NTN) are out of scope.
