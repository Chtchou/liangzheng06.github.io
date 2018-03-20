---
layout: page
title: Publication
---
<ul class="posts">
  {% for post in site.posts %}

    {% unless post.next %}
      <h3>{{ post.date | date: '%Y' }}</h3>
    {% else %}
      {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
      {% capture nyear %}{{ post.next.date | date: '%Y' }}{% endcapture %}
      {% if year != nyear %}
        <h3>{{ post.date | date: '%Y' }}</h3>
      {% endif %}
    {% endunless %}

    <li itemscope>
      <a href="{{ site.github.url }}{{ post.url }}">{{ post.title }}</a>
      <p class="post-date"><span><i class="fa fa-calendar" aria-hidden="true"></i> {{ post.date | date: "%B %-d" }} - <i class="fa fa-clock-o" aria-hidden="true"></i> {% include read-time.html %}</span></p>
    </li>

  {% endfor %}
</ul>

<h3><font size=4 face="Arial" color="#1772d0"><strong>Arxiv Papers</strong></font></h3>
                    <td>
                        <b>Person Re-identification: Past, Present and Future</b>
						<a href="https://arxiv.org/abs/1610.02984"><strong>[PDF]</strong></a><a href="https://github.com/zhunzhong07/IDE-baseline-Market-1501"><strong>[Baseline Code]</strong></a>
                        <br /><strong>Liang Zheng</strong>, Yi Yang, Alexander Hauptmann
                        <br />ArXiv:1610.02984, 2016.
                        <br /><br />
                    </td>


                    <td>
                        <b>Dual-Path Convolutional Image-Text Embedding</b>
						<a href="https://arxiv.org/abs/1711.05535"><strong>[PDF]</strong></a><a href="https://github.com/layumi/Image-Text-Embedding"><strong>[Code]</strong></a>
                        <br />Zhedong Zheng, <strong>Liang Zheng</strong>, Michael Garrett, Yi Yang, Yi-Dong Shen
                        <br />ArXiv:1711.05535, 2017.
                        <br /><br />
                    </td>	

                    <td>
                        <b>Random Erasing Data Augmentation</b>
						<a href="https://arxiv.org/abs/1708.04896"><strong>[PDF]</strong></a><a href="https://github.com/zhunzhong07/Random-Erasing"><strong>[Code]</strong></a>
                        <br />Zhun Zhong, <strong>Liang Zheng</strong>, Guoliang Kang, Shaozi Li, Yi Yang
                        <br />ArXiv:1708.04896, 2017.
                        <br /><br />
                    </td>	

                    <td>
                        <b>PatchShuffle Regularization</b>
						<a href="https://arxiv.org/abs/1707.07103"><strong>[PDF]</strong></a><strong>[Code coming soon]</strong>
                        <br />Guoliang Kang, Xuanyi Dong, <strong>Liang Zheng</strong>, Yi Yang
                        <br />ArXiv:1707.07103, 2017.
                        <br /><br />
                    </td>	

                    <td>
                        <b>Pedestrian Alignment Network for Large-scale Person Re-identification</b>
						<a href="https://arxiv.org/abs/1707.00408"><strong>[PDF]</strong></a><a href="https://github.com/layumi/Pedestrian_Alignment"><strong>[Code]</strong></a>
                        <br />Zhedong Zheng, <strong>Liang Zheng</strong>, Yi Yang
                        <br />ArXiv:1707.00408, 2017.
                        <br /><br />
                    </td>	

                    <td>
                        <b>Few-shot Object Detection</b>
						<a href="https://arxiv.org/abs/1706.08249"><strong>[PDF]</strong></a><strong>[Code coming soon]</strong>
                        <br />Xuanyi Dong, <strong>Liang Zheng</strong>, Fan Ma, Yi Yang, Deyu Meng
                        <br />ArXiv:1706.08249, 2017.
                        <br /><br />
                    </td>	

                    <td>
                        <b>Unsupervised Person Re-identification: Clustering and Fine-tuning</b>
						<a href="https://arxiv.org/abs/1705.10444"><strong>[PDF]</strong></a><a href="https://github.com/hehefan/Unsupervised-Person-Re-identification-Clustering-and-Fine-tuning"><strong>[Code]</strong></a>
                        <br />Hehe Fan, <strong>Liang Zheng</strong>, Yi Yang
                        <br />ArXiv:1705.10444, 2017.
                        <br /><br />
                    </td>	

                    <td>
                        <b>Improving Person Re-identification by Attribute and Identity Learning</b>
						<a href="https://arxiv.org/abs/1703.07220"><strong>[PDF]</strong></a><a href="https://vana77.github.io/"><strong>[Attributes]</strong></a>
                        <br />Yutian Lin, <strong>Liang Zheng</strong>, Zhedong Zheng, Yu Wu, Yi Yang
                        <br />ArXiv:1703.07220, 2017.
                        <br /><br />
                    </td>	
				
                    <h3><font size=4 face="Arial" color="#1772d0"><strong>Person Re-identification</strong></font></h3>
                    <td>
                        <b>CamStyle Augmentation</b>
						<a href="https://arxiv.org/abs/1711.10295"><strong>[PDF]</strong></a><strong>[Code coming soon]</strong>
                        <br />Zhun Zhong, <strong>Liang Zheng</strong>, Zhedong Zheng, Shaozi Li, Yi Yang
                        <br />CVPR, 2018.
                        <br /><br />
                    </td>	

                    <td>
                        <b>Image-Image Domain Adaptation with Preserved Self-Similarity and Domain-Dissimilarity for Person Re-identification</b>
						<a href="https://arxiv.org/abs/1711.07027"><strong>[PDF]</strong></a><a href="https://github.com/Simon4Yan/Learning-via-Translation"><strong>[Code]</strong></a>
                        <br />Weijian Deng, <strong>Liang Zheng</strong>,  Guoliang Kang, Yi Yang, Qixiang Ye, and Jianbin Jiao
                        <br />CVPR, 2018.
                        <br /><br />
                    </td>	
					<td>
                        <b>Unlabeled Samples Generated by GAN Improve the Person Re-identification Baseline in vitro.</b><a href="https://github.com/layumi/Person-reID_GAN"><font color=""><strong>[Code]</strong></font></a><a href="https://github.com/layumi/DukeMTMC-reID_evaluation"><font color=""><strong>[DukeMTMC-reID dataset]</strong></font></a>
                        <br />Zhedong Zheng, <strong>Liang Zheng</strong>, Yi Yang
                        <br />ICCV, 2017.
                        <br /><br />
                    </td>					
                    <td>
                        <b>SVDNet for Pedestrian Retrieval. </b><a href="https://github.com/syfafterzy/SVDNet-for-Pedestrian-Retrieval"><font color=""><strong>[Code]</strong></font></a>
                        <br />Yifan Sun, <strong>Liang Zheng</strong>, Weijian Deng, Shengjin Wang
                        <br />ICCV, 2017.
                        <br /><br />
                    </td>

                    <td>
                        <b>Dynamic Label Graph Matching for Unsupervised Video Re-Identification. </b><a href="http://www.comp.hkbu.edu.hk/~mangye/files/iccv17dgm2.pdf"><font color=""><strong>[PDF]</strong></font></a><a href="https://github.com/mangye16/dgm_re-id"><font color=""><strong>[Code]</strong></font></a>
                        <br />Mang Ye, Andy J Ma, <strong>Liang Zheng</strong>, Jiawei Li, Pong C Yuen
                        <br />ICCV, 2017.
                        <br /><br />
                    </td>

                        <b>Person Re-identification in the Wild</b>
                        <a href="https://arxiv.org/abs/1604.02531"><font color=""><strong>[PDF]</strong></font></a>
						<a href="Project/project_prw.html"><font color=""><strong>[Dataset]</strong></font></a>
                        <br /><strong>Liang Zheng*</strong>, Hengheng Zhang*, Shaoyan Sun*, Manmohan Chandraker, Yi Yang, and Qi Tian (* equal contribution)
                        <br />IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2017.
                        <br /><br />
                    <td>

                        <b>Re-ranking Person Re-identification with k-reciprocal Encoding</b>
                        <a href="http://zhunzhong.site/paper/person-ranking-cvpr.pdf"><font color=""><strong>[PDF]</strong></font></a>
						<a href="https://github.com/zhunzhong07/person-re-ranking"><font color=""><strong>[Code]</strong></font></a>
                        <br />Zhun Zhong, <strong>Liang Zheng</strong>, Donglin Cao and Shaozi Li
                        <br />IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2017.
                        <br /><br />
                    <td>
                        <b>MARS: A Video Benchmark for Large-Scale Person Re-identification</b>
                        <a href="1320.pdf"><font color=""><strong>[PDF]</strong></font></a>
						<a href="Project/project_mars.html"><font color=""><strong>[Dataset]</strong></font></a>
                        <br /><strong>Liang Zheng*</strong>, Zhi Bie*, Yifan Sun*, Jingdong Wang, Shengjin Wang, Chi Su, and Qi Tian (* equal contribution)
                        <br />European Conference of Computer Vision (ECCV), 2016.
                        <br /><br />
                    <td>
                        <b>Scalable Person Re-identification: A Benchmark</b>
                        <a href="ICCV15_scalable.pdf"><font color=""><strong>[PDF]</strong></font></a>
						<a href="Project/project_reid.html"><font color=""><strong>[Dataset]</strong></font></a>
                        <br /><strong>Liang Zheng*</strong>, Liyue Sheng*, Lu Tian*, Shengjin Wang, Jingdong Wang, and Qi Tian (* equal contribution)
                        <br />IEEE International Conference on Computer Vision (ICCV), 2015.
                        <br /><br />
                    <td>
                        <b>Query-Adaptive Late Fusion for Image Search and Person Re-identification</b>
                        <a href="CVPR15_query.pdf"><font color=""><strong>[PDF]</strong></font></a>
                        <a href="CVPR15_ext_abstract.pdf"><font color=""><strong>[Extended Abstract]</strong></font></a>
                        <a href="Project/project_fusion.html"><font color=""><strong>[Code]</strong></font></a>
                        <br /><strong>Liang Zheng</strong>, Shengjin Wang, Lu Tian, Fei He, Ziqiong Liu, and Qi Tian
                        <br />IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2015.
                        <br /><br />
                    <td>


                    <h3><font size=4 face="Arial" color="#1772d0"><strong>Instance Retrieval</strong></font></h3>

                        <b>SIFT Meets CNN: A Decade Survey of Instance Retrieval.</b><a href="https://arxiv.org/abs/1608.01807"><font color=""><strong>[PDF]</strong></font><a href="Project/surveybib.html"><font color="#1772d0"><strong>[Bibtex]</strong></font></a></a>
                        <br /><strong>Liang Zheng</strong>, Yi Yang, Qi Tian
                        <br />IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2017.
                        <br /><br />

                        <b>Packing and Padding: Coupled Multi-Index for Accurate Image Retrieval</b><!-- [<a href="publication/cvpr14-camready.pdf">PDF</a>]-->
                        <a href="CVPR14_cMI.pdf"><font color=""><strong>[PDF]</strong></font></a>
                       
                        <a href="https://onedrive.live.com/redir?resid=AFF7658EDB8F5E46%21108"><font color=""><strong>[Code]</strong></font></a>
                        <a href="Project/project_baseline.html"><font color=""><strong>[Baseline Project]</strong></font></a>
                        <br /><strong>Liang Zheng</strong>, Shengjin Wang, Ziqiong Liu, and Qi Tian
                        <br />IEEE Conference on Computer Vision and Pattern Recognition (CVPR), pp. 1947-1954, 2014.
                        <br /><font color="green">In case you cannot download the codes on OneDrive, we provide another link here </font><a href="http://pan.baidu.com/s/1kTigbqv"><font color=""><strong>[Code]</strong></font>.</a>
                        <br /><br />
                    <td>
                        <b>Bayes Merging of Multiple Vocabularies for Scalable Image Retrieval</b><!-- [<a href="publication/cvpr14-camready.pdf">PDF</a>]-->
                        <a href="CVPR14_bayes.pdf"><font color=""><strong>[PDF]</strong></font></a>
                        <a href="bayes_supplementary.pdf"><font color=""><strong>[Suppl.]</strong></font></a>
                        <a href="https://onedrive.live.com/redir?resid=AFF7658EDB8F5E46%21107"><font color=""><strong>[Code]</strong></font></a>
                        <a href="Project/project_baseline.html"><font color=""><strong>[Baseline Project]</strong></font></a>
                        <br /><strong>Liang Zheng</strong>, Shengjin Wang, Wengang Zhou, and Qi Tian
                        <br />IEEE Conference on Computer Vision and Pattern Recognition (CVPR), pp. 1963-1970, 2014.
                        <br /><font color="green">In case you cannot download the codes on OneDrive, we provide another link here </font><a href="http://pan.baidu.com/s/1i33JZ3v"><font color=""><strong>[Code]</strong></font>.</a>   
                        <br /><br />
                    <td>
                    </td>
                    <td>
                        <b>Lp-norm IDF for Large Scale Image Search</b>
                        <a href="CVPR13_pIDF.pdf"><font color=""><strong>[PDF]</strong></font></a>
                        <br /><strong>Liang Zheng</strong>, Shengjin Wang, Ziqiong Liu, and Qi Tian
                        <br />IEEE Conference
                        on Computer Vision and Pattern Recognition (CVPR), pp. 1626-1633, 2013.
<br /><br />
                    </td>
                        <b>Accurate Image Search with Multi-Scale Contextual Evidences.</b>
                        <br /><strong>Liang Zheng</strong>, Shengjin Wang, Jingdong Wang, and Qi Tian
                        <br />International Journal of Computer Vision (IJCV), accepted.</font><br /><br />
                    </td>
                    <td>
                        <b>Fast Image Retrieval: Query Pruning and Early Termination.</b>
                        <a href="TMM15_query.pdf"><font color=""><strong>[PDF]</strong></font></a>
                        <br /><strong>Liang Zheng</strong>, Shengjin Wang, Ziqiong Liu, and Qi Tian
                        <br />IEEE Transactions on Multimedia (TMM), 17(5): 648-659, 2015.</font><br /><br />
                    </td>
                    <td>
                    <td>
                        <b>Tensor Index for Large Scale Image Retrieval</b>
                        <a href="MMSJ15_tensor.pdf"><font color=""><strong>[PDF]</strong></font></a>
                        <br /><strong>Liang Zheng</strong>, Shengjin Wang, Peizhen Guo, Hanyue Liang, and Qi Tian
                        <br />Multimedia Systems, 21(6): 569-579, 2015.</font><br /><br />
                    </td>
                    <td>
                        <b>Coupled Binary Embedding for Large-scale Image Retrieval</b><!-- [<a href="publication/cvpr14-camready.pdf">PDF</a>]-->
                        <a href="TIP14_coupled.pdf"><font color=""><strong>[PDF]</strong></font></a>
                        <br /><strong>Liang Zheng</strong>, Shengjin Wang, and Qi Tian
