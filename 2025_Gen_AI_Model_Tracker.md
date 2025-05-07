speech, duplex

xtts v2
dia 1.6b
fish speech 1.5g tts
kyutai mushi
parakeet 0.6b asr nvidia
RealtimeVoiceChat (xtts v2)
Kimi-Audio 7b
csm, sesame (csm-1b)
megatts (bytedance)

(order of quality)
asr
parakeet, whispher

(order of quality)
tts
kokoro, fish speech, xtts

hexgrad/Kokoro-82M (tts)
metavoiceio/metavoice-src MetaVoice-1B is a 1.2B
/huggingface/parler-tts 2.3B, 880M


_______
Audio, tts, asr,speech

tencent/Hunyuan3D-1
ali-vilab/In-Context-LoRA
Kwai-Kolors/Kolors
InstantX/InstantID
THUDM/CogView3-Plus-3B
Alpha-VLLM/Lumina-Next-SFT-diffusers
Tencent-Hunyuan/HunyuanDiT-v1.2-Diffusers
Tencent-Hunyuan/HunyuanDiT
ByteDance/Hyper-SD
Shitao/OmniGen-v1
_______

image gen

(order of quality)
4o/sora, image gen 3, flux, midjourney
open
HiDream, Flux, SD 3.5, 

black-forest-labs/FLUX.1-dev
stable diffusion
HiDream-ai/HiDream-I1-Full

tencent/Hunyuan3D-1
ali-vilab/In-Context-LoRA
Kwai-Kolors/Kolors
InstantX/InstantID
THUDM/CogView3-Plus-3B
Alpha-VLLM/Lumina-Next-SFT-diffusers
Tencent-Hunyuan/HunyuanDiT-v1.2-Diffusers
Tencent-Hunyuan/HunyuanDiT
ByteDance/Hyper-SD
Shitao/OmniGen-v1
_______

video gen

(order of quality)
txt-2-vid
veo 2, runway gen 4, kling 1.5, sora, pika 2.2, minmax/wan/hunyuan/
img-2-vid
kling 1.6, runway gen 4, veo 2, minmax/wan/pika, sora, Hunyuan
open 
Hunyuan, Wan 2.1, Mochi, Cog, Pyramid flow, LTX

lllyasviel/FramePack (video gen on consumer gpu, grid/crossword compress)
Tencent/HunyuanVideo-I2V 
Tencent/HunyuanVideo
bytedance-research/UNO
Wan-AI/Wan2.1-T2V-14B
THUDM/CogVideoX-5b
Lightricks/LTX-Video
Wan-AI/Wan2.1-T2V-1.3B
genmo/mochi-1-preview
ByteDance/AnimateDiff-Lightning
ByteDance/InfiniteYou
MAGI-1: Autoregressive 24b, 4.5b
Bytedance UNO, Infinite You

LTX-V-2B
open-sora
mochi
Allegro
CogVideoX
Pyramid Flow
SVD 1.1 
__

hpcai-tech/Open-Sora-v2
stepfun-ai/stepvideo-t2v
Skywork/SkyReels-A1
Wan-AI/Wan2.1-T2V-14B
tencent/HunyuanVideo-I2V
stepfun-ai/stepvideo-ti2v
GSAI-ML/FlexWorld
Wan-AI/Wan2.1-FLF2V-14B-720P
Skywork/SkyReels-V2-I2V-14B-540P
Skywork/SkyReels-V2-I2V-1.3B-540P
_______

any-to-any (multi-modality)

Junfeng5/Liquid_V1_7B (byte dance)
0.5B, 1B, 2B, 7B, 9B, 32B, auto-regressive any-to-any
_______
video gen

wan 2.1

________

HiDream, Flux, SD 3.5
Hunyuan, Wan 2.1, Mochi, Cog, Pyramid flow, LTX

Bytedance
Infinite You (flux based)
AnimeDiff (SD1.5 based)
UNO (flux based)

MAGI-1: Autoregressive 24b, 4.5b
Junfeng5/Liquid_V1_7B (byte dance)
0.5B, 1B, 2B, 7B, 9B, 32B, auto-regressive any-to-any

Hunyuan
HiDream, Hunyuan, Wan 2.1
Flux, Mochi, SD 3.5
MAGI-1, Liquid_V1_7B

All Round (img, vid)
Hunyuan, Wan 2.1
Flux, Pyramid flow
Auto Regressive (faster generation)
MAGI-1, Liquid_V1_7B

___________________________


True, My open source rankings right now are 1) Mochi 2) Allegro 3) CogVideoX 4) Pyramid Flow 5) SVD 1.1 

There's also Hunyuan and LTX Video. 

Veo 2

16:9 (landscape) and 9:16 (portrait)

8s 720p

______________

Online Ones

veo 2, sora, runway, 
minimax, Kling
luma, pika labs

Everything at one place
https://www.krea.ai/

_____________________

Midjourney and Flux stills to Kling 1.6

google image gen 3 -> google veo 2 -> topaz labs project starlight (restoration) -> topaz labs upscaler

____________________



Ones I have not tested, but read about:

    Veo 2 - Seemingly the highest quality video model with semi-realistic physics and dynamic action supported, but it's hard to say, since very few have access to it yet.

These are some of the ones I've personally tested:

    Runway = Most Cinematic and movie like. Act one feature allows driving facial performances from video (on portraits mainly). Has a character consistency feature (though a bit of a pain to actually use it, especially for fictional 2D characters)

    Kling = Probably the best all arounder, aside from Veo2. Has Motion Brush controls (allows you to choose which direction things move using image to video, which is neat). Long wait times unless subscribed.

    PixVerse = Decent with Anime motion, but not great at prompt adherence. That's about all I tested it for.

    PikaLabs = Has the most amazing Ingredients feature that allows you to create consistent characters and environment across multiple videos (can't wait to see this in Kling / other models). Very Expensive (no unlimited plan) and the rendering is not as high quality as other models.

    Sora = Has a Loop feature, but otherwise...Not great. The best results I've gotten are from feeding it a video from another model and using it as an upscaler. The quality and coherence is among the poorest I've experienced across models. Very disappointing. Hope they shore things up with it.



