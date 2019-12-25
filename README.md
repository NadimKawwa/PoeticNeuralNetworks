  ![camel man](https://github.com/NadimKawwa/PoeticNeuralNetworks/blob/master/pics/camel_man_arabic.jpg)

# Poetic Neural Networks

In this repository we generate Arabic poetry using RNNs and Pytorch.
The poet in question is [Nizar Qabbani](https://en.wikipedia.org/wiki/Nizar_Qabbani) a native of Damascus, Syria. The reasons for selecting him are:
- Porlific writer
- Broad subjects covered therefore large vocabulary
- 11 year old me was forced to memorize some of his poems


## Getting Started
All code is written in Python 3.x, it is preferable to open the files using Jupyter Notebooks. All package dependecies are listed in the requirements.txt file.

The data is scraped from the internet and stored as independent .txt files in the data folder. The poems are then combined into one document under the raw_corpus.txt file.

## Output

The trained model is rather massive (100MB) and can't be hosted on GitHub. If you wish to obtain it feel free to shoot me an inmail on Linkedin or on twitter under the @Kunefeh handle.

Below is a sample poetry output limited to 5o characters:

<br>نحن عشته
لا تحسبي أن أحبك في البيادر<br>
في أخبار التاريخ,.<br>
تنقرض الأمة يعنيها.<br>
تنقرض الأمة من عارٍ فيها– الحداد..<br>
عيونها على ذراعيها..<br>
ومذيع الدولة في أجساد الأميره ؟<br>

يا رب أيـن ملتفٌ نسبي<br>

#### Rough translation:

We experienced it<br>
Do not think that I love you in the Gardens<br>
In history news ,.<br>
The nation becomes extinct.<br>
The nation becomes extinct from its disgrace - mourning ..<br>
Her eyes are on her arms ..<br>
And the state broadcaster in the princess's bodies?<br>
O Lord, where is the relative winding?<br>

