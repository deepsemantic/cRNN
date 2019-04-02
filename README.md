-To train model with standard normalization of attentive weights, please run: THEANO_FLAGS=mode=FAST_RUN,device=cuda0,floatX=float32 python cRNN_wikipedia_standard.py

-To train model with softmax of attentive weights, please run: THEANO_FLAGS=mode=FAST_RUN,device=cuda0,floatX=float32 python cRNN_wikipedia_softmax.py

-To train model with self-attentive weights, please run: THEANO_FLAGS=mode=FAST_RUN,device=cuda0,floatX=float32 python cRNN_wikipedia_attention.py
