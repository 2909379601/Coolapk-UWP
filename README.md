# Coolapk-UWP

**����һ����ȤʹȻ����Ŀ����ҪĿ������ѧϰUWPӦ�ÿ������Լ�C#����**

��Σ�Ϊ�˷�����Windows10(����δ����Windows X) ��ˢ�ᰲ

> **������������ѧϰ���о�;����������ҵ��;;**

### Ԥ��Ч��

#### ��ҳ��Ӧʽ����Ч��

![��ҳ��ʾЧ��1](https://imgtu.com/i/cyQQK0)

![��ҳ��ʾЧ��2](https://imgtu.com/i/cyQKvq)

![��ҳ��ʾЧ��3](https://imgtu.com/i/cyQu2n)

#### ͼ�Ķ�̬��ʾ

![ͼ�Ķ�̬��ʾЧ��](https://imgtu.com/i/cyQax1)

#### ͼ�ı༭��

![ͼ�ı༭��Ч��](https://imgtu.com/i/cyQ2RA)

### ����ᰲ��URI SCHEME
  - �򿪶�̬
    > coolmarket://feed/ + feed id

### ��Ҫ˵����Ŀ¼���ļ�����:

 - Assets ��Դ�ļ�
 - Controls �ؼ�
   - AsyncLoadStateControl.xaml ���һ����ȡ��ҳ���ṩ����״̬
   - DataList.xaml �����б�
   - MyRichTextBlock.xaml ���ı��༭��ʵ��
   - PicArrBox.xaml ����ͼƬ
   - ReplyList.xaml �ظ��б�
 - DataTemplates ģ��
   - EntityListItemDataTemplate.xaml �ṩһ��TemplateSelector�ͼ򵥵�ģ�����ڶ�̬�б�
   - FeedCardTemplates.xaml �Ͷ�̬�йص�Item��ģ��
   - FeedReplyTemplate.xaml �������йص�Itemģ���Լ�Selector
   - IconScrollCardTemplates.xaml
   - ImageTextScrollCardTemplate.xaml
   - PicTextMixTemplates.xaml ͼ��ģ��
 - Models ����ģ��
   - Entity.cs ������������ģ�͵Ļ���
 - Network �������
   - CoolapkApi.*.cs �ᰲApi
   - TokenHeaderHandler.cs Token���ɵ�
 - Other ��������
   - AppUtil.cs
   - IncrementLoadingCollection.cs
   - NotifyPropertyBase.cs
 - Pages ����ҳ��
 - Themes ...
 - ViewModels ��ͼģ��
   - BaseViewModel.cs ��ͼģ�ͻ���
 - App.xaml