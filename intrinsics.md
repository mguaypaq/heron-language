# Intrinsic Operations 

type radians (type degrees)
type degrees (type radians)
type sin (type angle)
type cos (type angle)
type tan (type angle)
type asin (type x)
type acos (type x)
type atan (type y, type x)
type atan (type y_over_x)
type pow (type x, type y)
type exp (type x)
type log (type x)
type exp2 (type x)
type log2 (type x)
type sqrt (type x)
type inversesqrt (type x)
type abs (type x)
type sign (type x)
type floor (type x)
type ceil (type x)
type fract (type x)
type mod (type x, float y)
type mod (type x, type y)
type min (type x, type y)
type min (type x, float y)
type max (type x, type y)
type max (type x, float y)
type clamp (type x, type minV, type maxV)
type clamp (type x, float minV, float maxV)
type mix (type x, type y, type a)
type mix (type x, type y, float a)
type step (type edge, type x)
type step (float edge, type x)
type smoothstep (type a, type b, type x)
type smoothstep (float a, float b, type x)
mat matrixCompMult (mat x, mat y)
float length (type x)
float distance (type p0, type p1)
float dot (type x, type y)
vec3 cross (vec3 x, vec3 y)
type normalize (type x)
type faceforward (type N, type I, type Nref)
type reflect (type I, type N)
type refract (type I, type N,float eta)
bvec lessThan(vec x, vec y)
bvec lessThan(ivec x, ivec y)
bvec lessThanEqual(vec x, vec y)
bvec lessThanEqual(ivec x, ivec y)
bvec greaterThan(vec x, vec y)
bvec greaterThan(ivec x, ivec y)
bvec greaterThanEqual(vec x, vec y)
bvec greaterThanEqual(ivec x, ivec y)
bvec equal(vec x, vec y)
bvec equal(ivec x, ivec y)
bvec equal(bvec x, bvec y)
bvec notEqual(vec x, vec y)
bvec notEqual(ivec x, ivec y)
bvec notEqual(bvec x, bvec y)
bool any(bvec x)
bool all(bvec x)
bvec not(bvec x)

