# Rigidbodyのpositionとrotationの固定について

##
```
// 回転、位置ともに固定
rigidbody.constraints = RigidbodyConstraints.FreezeAll;


// 回転しない設定
rigidbody.constraints = RigidbodyConstraints.FreezeRotation;


// 移動しない設定
rigidbody.constraints = RigidbodyConstraints.FreezePosition;


// 位置 X だけ固定
rigidbody.constraints = RigidbodyConstraints.FreezePositionX;
// 位置 Y だけ固定
rigidbody.constraints = RigidbodyConstraints.FreezePositionY;
// 位置 Z だけ固定
rigidbody.constraints = RigidbodyConstraints.FreezePositionZ;

// X軸 だけ固定
rigidbody.constraints = RigidbodyConstraints.FreezePositionX;
// Y軸 だけ固定
rigidbody.constraints = RigidbodyConstraints.FreezePositionY;
// Z軸 だけ固定
rigidbody.constraints = RigidbodyConstraints.FreezePositionZ;

// 位置 XY を 固定
rigidbody.constraints =
RigidbodyConstraints.FreezePositionX |
RigidbodyConstraints.FreezePositionY;

// 位置 YZ を 固定
rigidbody.constraints =
RigidbodyConstraints.FreezePositionY |
RigidbodyConstraints.FreezePositionZ;

// 位置 ZX を 固定
rigidbody.constraints =
RigidbodyConstraints.FreezePositionZ |
RigidbodyConstraints.FreezePositionX;

// XY軸 を 固定
rigidbody.constraints =
RigidbodyConstraints.FreezeRotationX |
RigidbodyConstraints.FreezeRotationY;

// YZ軸 を 固定
rigidbody.constraints =
RigidbodyConstraints.FreezeRotationY |
RigidbodyConstraints.FreezeRotationZ;

// ZX軸 を 固定
rigidbody.constraints =
RigidbodyConstraints.FreezeRotationZ |
RigidbodyConstraints.FreezeRotationX;
```