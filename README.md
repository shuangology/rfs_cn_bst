# rfs_cn_bst
Chinese version of RFS (Review of Financial Studies) bibliography style

一个RFS风格的中文参考文献格式文件

The file 'rfsnew_CN.bst', is modified from Patrick W Daly's version in 2007, downloaded from https://github.com/tevgeniou/FinanceProjectTemplate.git

This bibliography style file now works for text in Chinese.

This is an author-year citation style bibliography, mainly adopted in Finance/Economics study.

The original source files were:

merlin.mbs  (with options: 'ay,nat,nm-rev1,jnrlst,keyxyr,blkyear,dt-beg,yr-per,note-yr,atit-u,vnum-x,num-xser,ser-ed,jnm-x,add-pub,pre-edn,edpar,pp,ed,abr,ednx,ord,and-com,etal-xc,url,url-blk,nfss,')


The \cite command functions as follows:

\citet{key} ==>>                Jones 等. (1990)

\citet*{key} ==>>               Jones, Baker, 和 Smith (1990)

\citep{key} ==>>                (Jones 等., 1990)

\citep*{key} ==>>               (Jones, Baker, 和 Smith, 1990)

\citep[chap. 2]{key} ==>>       (Jones et al., 1990, chap. 2)

\citep[如，][]{key} ==>>        (如， Jones et al., 1990)

\citep[e.g.][p. 32]{key} ==>>   (e.g. Jones et al., p. 32)

\citeauthor{key} ==>>           Jones 等.

\citeauthor*{key} ==>>         Jones, Baker, and Smith

\citeyear{key} ==>>             1990
