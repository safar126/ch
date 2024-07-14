dat5={
  "app": "com.olzhas.carparking.multyplayer2",
  "duration": "215ms",
  "headers": {
    "Content-Type": "application/json",
    "X-Firebase-Client": "H4sIAAAAAAAAAKtWykhNLCpJSk0sKVayio7VUSpLLSrOzM9TslIyUqoFAFyivEQfAAAA",
    "X-Android-Package": "com.olzhas.carparking.multyplayer2",
    "X-Android-Cert": "004A4780B060C9F35B7C9868D1D50379B79940DF",
    "User-Agent": "Dalvik/2.1.0 (Linux; U; Android 11; RMX2195 Build/RKQ1.201217.002)",
    "Host": "firebaseappcheck.googleapis.com",
    "Connection": "Keep-Alive",
    "Accept-Encoding": "gzip"
  }}

def getsuth():
	try:
		#dat= open('firebase.txt').read()
		uri='https://firebaseappcheck.googleapis.com/v1/projects/cpm-2-7cea1/apps/1:891105416504:android:37d689c257df3c37b19dcd:exchangePlayIntegrityToken?key=AIzaSyCQDz9rgjgmvmFkvVfmvr2-7fT4tfrzRRQ'
		data={"playIntegrityToken":"eyJhbGciOiJBMjU2S1ciLCJlbmMiOiJBMjU2R0NNIn0.yzMLVJe5xn8knE0KP_1Zy0Q_ck-mZB84KGmUJ4X0irUnlbi9dxWCWg.cw05YFTNc_mnD2YV.Wbr2SLosE2ZYbEoDaXTRg2_U1dcoH3ax8xqoM-_uFUd1LvB5Q5l4V6x2MpBiuRB_sKSb_A5Vys7RpXBb_uJbK5hQ9Kf9DRqulXPV5e4wyt5oV1PSdSGhf9wiSBPnBOEMIsRsPi9tnoNGc0cXXvopO7Mo-Monw3BUYHMhwKyx0bfrCgF2qPPf2oQyI98SNvG2IIUEu2Evkaaa_9bdOXzCodHT8Bmd2dpWZObQ3c9FNjEW65LJ47-R7SjiGOru3_laADLjZqKhdds_Nlj6GnLKiSHCEZYfyFytQPTWwtzMVck5P7xGfgffgq8-EkHgCIyuzY7V8ndnQlDwPh80n-zN5jNXRgzeRqb4oywm-YgEvlop8FNzC5tEg8ZMZ0BzwHvdOWZVELbX66gDvdvbKtYjFvnYnguwPYyWltVFOHU4DvjNxVJfrTcykKs9cUv_qhczDT6nn4ku5vEgxaovoDa7mE3shQCcE4AhnVONmhAH76A9hgeqCC80fOHtYx-p3D5K36A-F3pPztIPdgsKuDa9SDclFhumj4IT4iKnLvkWVOfOiP7nviMXQuvA3__QbzCdY_q-bFBB1iVYjprBzdAF1w7TQw8sK3SUVsqp70WFoh54Fn72ULsikKSn-17SKueOWacij6m4CvSJafLBYOYwy3xpRyzsZSiuYZY5uMIC-sTbJ8CAQwkJEL1NHNvOK-v97JndWXb0c1zcF3VSZkf0KN3ULXsXI89mm-d-0IWzsqZsbEhe5c_LK_D-5HdjioAWAY7NOn8B9J1FYZ3QEgaOPr3yqSMdKzxaurJanIuxQcV6CF7zWm6rZqyMZSt0Fp6SrxOkz5FuUKoyxiv9BYDMpISrCv7nk3HpuO9Z1-Q5osDLqdNZwYUPlRf0lFSnxHgWNFYWupLREwu7ofx1SSnaDytSdEIy2WBG__qvPmSE6GG_bFfuHhAEALatyAG4b1Z1rDzdXbwdYK6rVhG6jCcASCL4HZc3QfMl3qQZDxYuGindsDtWSCqTEnOgazkN_LJU41MDSHIHwp8h6OQIeFoKOaT9-M4y6ET447SbPQRdMFBga4gzdtA2Nl7ODjV7xk66e58kmoHPPcK5DiRyoEzATk7mmvkD8-A6ev_gGp0I1XgJIAdveCjqBQmCmF-zFSGMcN2CvntROKnLOZ5dJHchg_Hgr0oYBAhjzXy_DYJ6nyd23cP9UeXUVZZiuGegg5gOe1NrHFbkkeB6OMH59AYRqDlFVj42yy_1csNVpj0HfkxnkzIaNf7iGhtbw9lcUgr6NH0BiLFS2ifNXUKYr5lHQlEMUMxXrC5Zr7qjwN_I0FiRDZK5_S0MY7jbc1uqCiAiFWovD5OiNQXlO3zCPHuQ_aiAj1TwqIM7fXbObf3ov9XY3YjXAeLJE9WR3pRk15UlBY4ruNzQ-0VvTOJ3mFFWbyPH.gXk0_b249BW1iz2hKl02Ag"}
		
		print(json.dumps(data))
		req=httpx.post(uri,data=json.dumps(data),headers=dat5['headers'],timeout=200)
		print(req.text)
	except Exception as e:
		print(e)
