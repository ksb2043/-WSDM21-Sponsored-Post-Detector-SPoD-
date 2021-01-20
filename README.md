# [WSDM'21] Sponsored Post Detector (SPoD)

The transparency issue of sponsorship disclosure in advertising posts has become a significant problem in influencer marketing. Despite the fact that influencers are urged to comply with the regulations governing sponsorship disclosure, a considerable number of influencers fail to disclose sponsorship properly in paid advertisements. In this paper, we propose a learning-to-rank based model, SponsoredPost Detector (SPoD), to detect undisclosed sponsorship of social media posts by learning various aspects of the posts such as text, image, and the social relationship among influencers and brands. More precisely, we exploit image objects and contextualized information to obtain the representations of the posts and also utilize Graph Convolutional Networks (GCNs) on a network which consists of influencers, brands, and posts with embed social media attributes. We then apply attention mechanism over different aspects of the posts to utilize more important features for discovering undisclosed sponsorship. We further optimize the model by conducting manifold regularization based on temporal information and mentioned brands in posts. The extensive studies and experiments are conducted on sampled real-world Instagram datasets containing 1,601,074 posts, which mention 26,910 brands, published over 6 years by 38,113influencers. Our experimental results demonstrate that SPoD significantly outperforms the existing baseline methods in discovering sponsored posts on social media.

