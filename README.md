# ossuitil-downlaoding-issue
Issue met when downloading files to HPC

(base) [medkwf4@data ossutil]$ ./ossutil64 cp -r oss://skyseq-product/0019000001zJxpKAAS/YUEER-20220609-L-01-2022-06-131628 /lustre/home/acct-medkwf/medkwf4/ngs/hpctraining/rnaseq/scripts

average speed 0(byte/s)
Error: Get "http://skyseq-product.oss-cn-shanghai.aliyuncs.com/?delimiter&encoding-type=url&marker&prefix=0019000001zJxpKAAS%2FYUEER-20220609-L-01-2022-06-131628": dial tcp 139.227.226.196:80: connect: no route to host, Bucket=skyseq-product, Object=

Seems like connection problem
Run successfully on Nuprobe Shanghai server with the same config
Not solved by changing to data transmission node
