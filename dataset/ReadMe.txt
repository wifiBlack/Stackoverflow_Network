About Dataset

Source
https://www.kaggle.com/datasets/stackoverflow/stackoverflow-tag-network

Context
On the data team at Stack Overflow, we spend a lot of time and energy thinking about tech ecosystems and how technologies are related to each other. One way to get at this idea of relationships between technologies is tag correlations, how often technology tags at Stack Overflow appear together relative to how often they appear separately. One place we see developers using tags at Stack Overflow is on their Developer Stories, or professional profiles/CVs/resumes. If we are interested in how technologies are connected and how they are used together, developers' own descriptions of their work and careers is a great place to get that.

Content
A network of technology tags from Developer Stories on the Stack Overflow online developer community website.

This is organized as two tables:

stack_network_links contains links of the network, the source and target tech tags plus the value of the the link between each pair
stack_network_nodes contains nodes of the network, the name of each node, which group that node belongs to (calculated via a cluster walktrap), and a node size based on how often that technology tag is used

Acknowledgements
All Stack Overflow user contributions are licensed under CC-BY-SA 3.0 with attribution required.
