1. �˹�����ʹ��VS2010 RC�汾�����ġ�
2. flex_bisonĿ¼���ǣ�flex++��bison++��ͨ��CLexer.l��CParser.y����CLexer.h��CLexer.cc��CParser.h��CParser.cc�Ĺ��ߡ�

�����ǣ�
cd $(ProjectDir)
..\flex_bison\bison++ -d  -o CParser.cc -h CParser.h CParser.y
..\flex_bison\flex++ -8 -hCLexer.h -oCLexer.cc CLexer.l

ÿ���޸�CLexer.l��CParser.y��ͨ�������������ɶ�Ӧ��ͷ�ļ�������ļ���
�����ʹ��VS2010���˲����Ѿ��ڹ����趨���趨�ˣ�ÿ�α���ǰ��ִ����������Ȼ����б��롣��
